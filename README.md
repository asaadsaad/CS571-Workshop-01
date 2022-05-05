# CS571 Workshop 01
## Contacts Workshop
* Create a new React Native application with Expo CLI. 
* Copy the `contacts.js` file into your project and install `react-native-uuid` and `buffer` dependencies. Examine the file content and note that this file has a default export for an array of `contacts`, and two other exported methods: 
  * `compareNames` to sort an array of objects by `name`
  * `generateUUID` to generate a unique ID for contacts
* Add two buttons to `App` to toggle displaying the following components:
  * `ListContacts`: List of contacts.
  * `NewContact`: Add new contact.
* Create a reusable `Contact` functional-component that displays a single contact (`name` and `phone`). Validate all `props` types.
* Display all contacts in `App` class-component using `ScrollView` component.
* Replace `ScrollView` with `FlatList` component and notice the performance difference with a big number of contacts.
* Add a button to `App` component to sort the contacts alphabetically, use the `compareNames()` method from `contacts.js`.
* Add a button to `App` component to display a form for adding a new contact:
  * Create `NewContact` functional-component and handle adding the form values (both `name` and `phone`) where `phone` has to be 10 digits number. 
