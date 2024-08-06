# SemiOS-Protocol-PM
Everything there is to know about SemiOS Protocol

Process Content

I. Tracking Feature Launch

II. Task Completion Status

III. Template Setup

---

### I. Requirement Tracking

#### 1.1. Product Requirement Import, which can be a single issue or multiple issues

a. When a customer raises a requirement for a specific version, it can be turned into a standalone issue.

b. The product team submits the issue under the "PM" repository.

c. When submitting an issue, please choose the [feature] template to create it. The feature label will be added by default, and other labels can be added as needed.

#### 2. After the product completes the issue creation, create a milestone.

a. The milestone can be the version number. Clearly describe the milestone goal and completion time.

#### 3. The completion of the above steps can be done after the requirement review.

#### 4. The internal process of Product Design - Requirement Review - UI Design - UI Review remains unchanged.

---

### II. Task Tracking

#### 1. After the requirement review is confirmed, the PM needs to create a progress tracking issue. This is to plan the progress for everyone — tentatively, this will be done through the project to manage progress in the future.

a. The internal process remains unchanged. Email synchronization of version plans will run in parallel with the issue announcements. (Currently in parallel, will be replaced in the future.)

#### 2. Development Phase: After the requirement review, move into development. Complete locally.

a. Each developer needs to fork the GitHub code using the dedicated GitHub account for this project.

b. Developers will then fork it again locally using the common account. (For multi-developer scenarios, the fork path is: semios - common account - local1/local2)

c. During development, test code writing needs to be completed simultaneously.

#### 3. Integration - Testing - Release: The process remains unchanged, following the current method.

#### 4. After passing the test, the project is released to the delivery environment. Code is submitted to GitHub.

a. Once the project is released to the production environment, each developer will submit a pull request via the common account.

b. Upon approval, code merging is completed and tagged.

c. This marks the completion of the current iteration delivery.

#### 5. After the delivery goes live, any issues found should be submitted as issues in the corresponding GitHub repository.

a. Issues need to be submitted under the corresponding repository, clearly labeled to indicate which end the problem is related to, and associated with the corresponding project.

---

### III. Template Setup

#### 1. Label Definitions

a. Status Labels: S-Completed, S-Pending, S-Rejected, S-Deferred

b. Team Labels: T-Frontend, T-Backend, T-Contract, T-Product, T-Test

c. Type Labels: bug, question, feature

d. Priority Labels: P0, P1, P2

#### 2. Issue Submission Templates

a. bug

b. feature
