# Tasks: Football Role Guide Static Website

## Phase 1: Setup
- [x] T001 Create project directory structure per plan.md
- [x] T002 Initialize npm project in root
- [x] T003 Install Vue.js 3, Vite, and Vitest dependencies
- [x] T004 Create initial README.md in project root
- [x] T005 Create MIT LICENSE file in project root

## Phase 2: Foundational
- [x] T006 Create src/ directory and base Vite config
- [x] T007 Create src/main.js and src/App.vue for Vue entry
- [x] T008 Create src/assets/ for images and styles
- [x] T009 Create src/components/RoleBox.vue for role display
- [x] T010 Create src/data/roles.js with role data structure from data-model.md
- [x] T011 Add base CSS for responsive, clean design

## Phase 3: User Story 1 - Browse Football Roles (P1)
- [x] T012 [US1] Implement Role entity structure in src/data/roles.js
- [x] T013 [US1] Implement RoleBox.vue to display name, image, and description
- [x] T014 [US1] Render grid of RoleBox components in App.vue
- [x] T015 [US1] Add placeholder images for roles in src/assets/
- [x] T016 [US1] Validate that all roles display with name, image, and description

## Phase 4: User Story 2 - Visual Clarity and Clean Design (P2)
- [x] T017 [US2] Refine CSS for grid layout and mobile responsiveness
- [x] T018 [US2] Test layout on multiple screen sizes
- [x] T019 [US2] Adjust RoleBox and App.vue for accessibility (contrast, alt text, keyboard nav)
- [x] T020 [US2] Validate visual clarity and responsiveness

## Phase 5: User Story 3 - Learn How to Play Each Role (P3)
- [x] T021 [US3] Write structured descriptions for each role (divided into titled sections)
- [x] T022 [US3] Display each description section with title and body in RoleBox.vue
- [x] T023 [US3] Validate that descriptions are clear and actionable

## Final Phase: Polish & Cross-Cutting
- [x] T024 Add error handling for missing images (show placeholder)
- [x] T025 Add MIT license and project info to README.md
- [x] T026 Add npm scripts for build, test, and preview
- [x] T027 Run Vitest tests for all components
- [x] T028 Review and clean up code and documentation

## Dependencies
- Phase 1 must be completed before Phase 2
- Phase 2 must be completed before any User Story phases
- User Story phases (3, 4, 5) can be worked on in parallel after foundational setup
- Final Phase can be started after all User Story phases are complete

## Parallel Execution Examples
- [ ] T012 [P] [US1] Implement Role entity structure in src/data/roles.js
- [ ] T017 [P] [US2] Refine CSS for grid layout and mobile responsiveness
- [ ] T021 [P] [US3] Write structured descriptions for each role

## Implementation Strategy
- MVP: Complete all tasks for User Story 1 (Phase 3)
- Incrementally deliver User Story 2 and 3 in parallel after MVP
- Polish and cross-cutting tasks after all user stories are implemented
