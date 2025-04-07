# NgRx

## What is NgRx?

**NgRx is a State Management Solution -> Aims to help with the management of more complex, (app-wide) state**

**State is data in components that changes over time (Button clicks) -> Changes should be reflected (in UI) -> May be used instead of managing complex state in components or services**

<br>

## Store

**Store - This is where your data is stored and managed**

    |
    V

**Selector used for communication between Store and Component**

    |
    V

**Component - This is where the data is needed and updates should be reflected**

Component can read data from the store ("listen to changes")

    |
    V

**Action - Standardized messages ("events") to which reducers can listen**

    |
    V

**Reducer - Contains state changing logic (e.g., incement counter by 1)**

<br>

<img src="./src//app/shared/images/state-management-lifecycle.png">