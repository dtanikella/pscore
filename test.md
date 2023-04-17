<!--@@joggrdoc@@-->
<!-- @joggr:version(v1):end -->
<!-- @joggr:warning:start -->
<!-- 
  _   _   _    __        __     _      ____    _   _   ___   _   _    ____     _   _   _ 
 | | | | | |   \ \      / /    / \    |  _ \  | \ | | |_ _| | \ | |  / ___|   | | | | | |
 | | | | | |    \ \ /\ / /    / _ \   | |_) | |  \| |  | |  |  \| | | |  _    | | | | | |
 |_| |_| |_|     \ V  V /    / ___ \  |  _ <  | |\  |  | |  | |\  | | |_| |   |_| |_| |_|
 (_) (_) (_)      \_/\_/    /_/   \_\ |_| \_\ |_| \_| |___| |_| \_|  \____|   (_) (_) (_)
                                                              
This document is managed by Joggr. Editing this document could break Joggr's core features, i.e. our 
ability to auto-maintain this document. Please use the Joggr editor to edit this document 
(link at bottom of the page).
-->
<!-- @joggr:warning:end -->
# Code Walkthrough for _Name_

_A brief description of the code being walked through._

## Requirements

- _Add any requirements here._

## Getting Started

### Step 1 - _Name of the step_
<!-- @joggr:snippet(6ef70a47-c0c1-4cec-bb5f-2ee356e28b12):start -->
```java
    @Override
    public boolean onCreateOptionsMenu(Menu menu) {
        // Inflate the menu; this adds items to the action bar if it is present.
        getMenuInflater().inflate(R.menu.menu_log_poop, menu);
        return true;
    }
    //comment whatever
```
<!-- @joggr:snippet(6ef70a47-c0c1-4cec-bb5f-2ee356e28b12):end -->
<!-- @joggr:snippet(23b6df87-6418-4f6a-a575-bba0f1ddf345):start -->
```javascript
const styles = {
  fontFamily: 'sans-serif',
  textAlign: 'center',
};
```
<!-- @joggr:snippet(23b6df87-6418-4f6a-a575-bba0f1ddf345):end -->


_Add a description of the step here._

_Add a code snippet here._

### Step 2 - _Name of the step_

_Add a description of the step here._

_Add a code snippet here._

### Step 3 - _Name of the step_

_Add a description of the step here._

_Add a code snippet here._

## :tada: Done

_Add a description of the completed task here._

## Resources

- _Add any related resources here._
<!-- @joggr:editLink(78e4bf08-ba12-4ca5-9e31-e2c42fbddb9a):start -->
---
<a href="https://app.joggr.io/app/documents/78e4bf08-ba12-4ca5-9e31-e2c42fbddb9a/edit" alt="Edit on Joggr">
  <img src="https://img.shields.io/static/v1?label=&message=Edit%20doc%20on%20Joggr&style=for-the-badge&color=349ACA&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgCAYAAABzenr0AAAACXBIWXMAAAsTAAALEwEAmpwYAAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAQOSURBVHgBtVdNTBNBFH67UBQK0vIPwUhBDngAjB4EE4GInssd4lHwIgl6Bs7EBC7CEQNn4Y5G8SAXE4EDHlCpP+GnAi0pYKQWfN90p0zbbbst+CVNd2ffzvfmve+9mdXIItbW1hwFBQVuTdPa+Nd8cnJSw8MO47Gfxzw8tsi/+UAgMOtyufxW5tVSGWxsbNTYbLZ+JnigEFrB5NHR0XBlZaWHMnEAK2YMHh8f99PZMKrr+rDT6fRbdgCrzsnJecOXNXQ+8HA0OsyiEeeA1+ttzsrKmkmH/Iv/Dw0vbNHWYZDuXSmgvqYSstv0OCdCoVBXWVnZojoYZYWVp0sOSHJg7luAXq7umZmJucFh6gBynknY94PHEXIJb8y96gQ4fD6fI84BCI4yyHk+h7qxNDdqLPY+1gkW9qC8ERowRLdGFjDzeY/erx8Ikp4GpxjbOvxLszy+eRCk1iq70IFqj+ewVXXBonRBlNm44TofskK+wMQTS9vievnXb/rK4ntys4zK87LpYWNxnP30Jx9NreyK64rcbHLXF0aeobfwX7+GfHBIfKnIsYq+Vz/ogHOuAuQjd6qo3G6LGsfKpbPA87vVVOe4oJr4uT+4dC4NN1kgfzq/HiG/zyEuz7OdPnu3LkpRQo0U0MfRiSEHHMFg0I2ktFMSgBTkUunI8QCHfaStKsqJR69/Ch3geuSDN/J+N+feXW/ewbks27Td3d2PvIE0J3JgYnmHZlbDXRThHu+8HBETSvAZk0GUEngmI9V1tZB6uSklwaJu7GqmwMQqOXKtKhklONhSEakGQJI3cZWkIAdqUAUJd7h8g8xuEEmhTbG6QdRVd0mMdV8rErbjHC3p7MCNUrIAh7azs3OSzAI5xeRy5WppxVYAbFGe0InJXmAKOIAStLTPq+QScA69oIVJM4Bfx0nGiiVKSyWvLQyXFYQ4tLAp0pIBPDo3oaVUVmalNd5ZzSo/Ddw0Oyc1kAYWkai3lIJcbUIorR4WHdDbVBxVAbNcMVMr1iOB86POzWCWrxMeIBF22YTQzWJLCxUgGxKgpTxlngLcOs5q7MmLREaIAADFD94qN7XZD4YiNoiQRUyCW/jLGxL26KjtGL197vs+tVbmCScaSy7GbThIC8quliMz5wnwNpwfZ5MI2IjYgfB2jIvt7e0xrojH0gAtGJMfHIVE7zcD1A+b7oYi1oWTrIIjPgZO4Ygc5HwM8Z9H3t/mlSPnrUnqGzZAhT2b0oDH4BKIkoyRivM8jseRc+g75OqBqH6JBzg6kxKJcybvUskB06L5D5GIW7mE6Y4BQ37hOsRCZwTmwFxm5EDKtoFocFqGjI9TqxC9hcU2mojYsgOKIw7j/NjOzjRROD2Rz3MK60Z8nqPDJfoYjcU/YCD1KmTczqkAAAAASUVORK5CYII=" />
</a>
<!-- @joggr:editLink(78e4bf08-ba12-4ca5-9e31-e2c42fbddb9a):end -->