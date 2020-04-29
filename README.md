# CS571 Workshop 01
## Contacts Workshop
* Create a new React Native application with Expo CLI. 
* Add `contacts.js` file to your project and install `react-native-uuid` and `buffer` dependencies. This file has a default export for an array of `contacts`, and two exported methods: `compareNames` and `generateUUID`, the first is used to sort an array of objects by `name`, and the later is used to generate a unique ID for every contact.
* Create a reusable `Contact` component that displays a single contact.
* Display all contacts using `ScrollView` component.
* Add a button to toggle displaying the list of contacts.
* Replace `ScrollView` with `FlatList` component.
* Add a button to sort the contacts alphabetically, use `compareNames()` method provided with `contacts.js`.
* Add a button to display a form for adding a new contact.
* Create `AddContactForm` component and handle validating the form values.
* Write an own algorithm to convert the contacts array into a different data-structure that `SectionList` component can work with.
* Display list of contacts with `SectionList` component.
