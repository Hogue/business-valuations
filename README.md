#Mlive Front-End Readme

###File Structure

####html is broken into three categories: Main Views, States, Modals

#### Main Views `/resources/views`
There are two categories of main views — Submission and Management

###### Submission Views
- `/resources/views/submission-final-details.blade.php`
- `/resources/views/submission-landingpage.blade.php`
- `/resources/views/submission-narrative.blade.php`
- `/resources/views/sample-story.blade.php`

###### Management Views
- `/resources/views/management-home-dashboard.blade.php`
- `/resources/views/management-landing.blade.php`

#### States `/resources/views/states`
States are components of main views that are injected via `@includes` within the main views. For example, each column within the management dashboard is its own state, and all three are injected into the main dashboard view. Like the main views, states are also broken up by management and submission.

###### Submission States
- `/resources/views/states/submission-landing-final.blade.php`
- `/resources/views/states/submission-landing-initial.blade.php`
- `/resources/views/states/submission-narrative-one.blade.php`
- `/resources/views/states/submission-narrative-two.blade.php`

###### Management States
- `/resources/views/states/management-column-new.blade.php`
- `/resources/views/states/management-column-ready.blade.php`
- `/resources/views/states/management-column-working.blade.php`
- `/resources/views/states/management-landing-forgot-pass-confirmation.blade.php`
- `/resources/views/states/management-landing-forgot-pass.blade.php`
- `/resources/views/states/management-landing-signin.blade.php`

#### Modals `/resources/views/modals`
Like States, Modals are stored separtely and injected through `@includes`. There is only one modal that applies to the submission side, and that's `/resources/views/modals/submission-upload-limits.blade.php` — the rest are associated with management.

###### Submission Modals
- `submission-upload-limits.blade.php`

###### Management Modals
- `/resources/views/modals/story-rejected.blade.php`
- `/resources/views/modals/story-more-info.blade.php`
- `/resources/views/modals/story-detail-working-editing.blade.php`
- `/resources/views/modals/story-detail-rejected.blade.php`
- `/resources/views/modals/story-detail-rejected-notification.blade.php`
- `/resources/views/modals/story-detail-ready.blade.php`
- `/resources/views/modals/story-detail-notification.blade.php`
- `/resources/views/modals/story-detail-no-notification.blade.php`
- `/resources/views/modals/story-detail-new.blade.php`
- `/resources/views/modals/story-detail-finished.blade.php`
- `/resources/views/modals/change-password.blade.php`



######Scss
all scss files can be found here `/resources/assets/sass`
