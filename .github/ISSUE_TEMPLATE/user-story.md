---
name: User Story
about: This template defines a user story
title: ''
labels: ''
assignees: ''

---

User Story: GiftLink Full-Stack Web Application

As a user who wants to give away or find free household items
I need a comprehensive web platform that connects givers and receivers
So that I can reduce waste by rehoming items I no longer need or find quality pre-owned items without purchasing new ones

Details and Assumptions

- The application serves two primary user types: givers (who want to donate items) and receivers (who want to find free items)
- Users must be able to register, login, and manage their profiles
- The platform includes item listings with detailed information and search capabilities
- The application follows a full-stack architecture with both frontend and backend components
- Users can browse items without registration but need accounts to post listings or contact item owners
- The interface includes: home page, listings page, navigation bar, search functionality, item details page, registration page, login page, and editable profile page
- Items are household goods that are still functional but no longer needed by the original owner

 Acceptance Criteria

Given I am a new user visiting GiftLink
When I navigate to the home page
Then I should see an overview of the platform, featured listings, and clear navigation options

Given I want to find specific household items
When I use the search function with keywords or categories
Then I should see relevant listings that match my search criteria

Given I am an unregistered user interested in an item
When I click on an item listing
Then I should see detailed information about the item and be prompted to register/login to contact the owner

Given I want to join the GiftLink community
When I complete the registration form with valid information
Then I should have a new account and be able to access member features

Given I am a registered user with items to give away
When I create a new listing with item details and photos
Then my listing should appear in the appropriate category and be searchable by other users

Given I am a registered user
When I access my profile page
Then I should be able to view and edit my personal information, see my active listings, and manage my account settings

Given I am a registered user interested in an item
When I contact the item owner through the platform
Then the owner should receive my message and be able to respond

Given I am browsing available items
When I navigate through the listings page
Then I should see items organized in a user-friendly format with filtering and sorting options
