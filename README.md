<!-- Generated by documentation.js. Update this documentation by updating the source code. -->

### Table of Contents

-   [Usage][1]
-   [License][2]
-   [Terms of Service][3]
-   [Main][4]
    -   [getConfig][5]
        -   [Parameters][6]
    -   [getData][7]
        -   [Parameters][8]
    -   [getSchema][9]
        -   [Parameters][10]
    -   [isAdminUser][11]
-   [Auth][12]
    -   [authCallback][13]
        -   [Parameters][14]
    -   [get3PAuthorizationUrls][15]
    -   [getAuthType][16]
    -   [getOAuthService][17]
    -   [isAuthValid][18]
    -   [resetAuth][19]
-   [Utils][20]
    -   [buildRows][21]
        -   [Parameters][22]
    -   [deriveSchema][23]
        -   [Parameters][24]
    -   [requestPCO][25]
        -   [Parameters][26]

## Usage

-   TODO List Install and Setup.


## License

-   TODO License


## Terms of Service

-   TODO TOS?      


## Main




### getConfig

-   **See: [https://developers.google.com/datastudio/connector/reference#getconfig][27]
    **

Returns the user configurable options for the connector.

#### Parameters

-   `request` **[object][28]** A JavaScript object containing the config request parameters.

Returns **[object][28]** A JavaScript object representing the config for the given request.

### getData

#### Parameters

-   `request` **any** 

Returns **any** 

### getSchema

#### Parameters

-   `request` **any** 

Returns **any** 

### isAdminUser

Returns **[boolean][29]** 

## Auth




### authCallback

The OAuth callback.

#### Parameters

-   `request` **[object][28]** The request data received from the OAuth flow.

Returns **HtmlOutput** The HTML output to show to the user.

### get3PAuthorizationUrls

-   **See: [https://developers.google.com/apps-script/reference/script/authorization-info][30]
    **

Gets the 3P authorization URL.

Returns **[string][31]** The authorization URL.

### getAuthType

Returns the Auth Type of this connector.

Returns **[object][28]** The Auth type.

### getOAuthService

Returns the configured OAuth Service.

Returns **Service** The OAuth Service

### isAuthValid

Returns true if the auth service has access.

Returns **[boolean][29]** True if the auth service has access.

### resetAuth

Resets the auth service.

## Utils




### buildRows

#### Parameters

-   `selectedFields` **any**  (optional, default `[]`)
-   `rawApiData` **any**  (optional, default `[]`)

Returns **any** 

### deriveSchema

#### Parameters

-   `attributes` **any** 

Returns **any** 

### requestPCO

#### Parameters

-   `selectedAPI` **any** 
-   `options` **any**  (optional, default `{}`)

Returns **any** 

[1]: #usage

[2]: #license

[3]: #terms-of-service

[4]: #main

[5]: #getconfig

[6]: #parameters

[7]: #getdata

[8]: #parameters-1

[9]: #getschema

[10]: #parameters-2

[11]: #isadminuser

[12]: #auth

[13]: #authcallback

[14]: #parameters-3

[15]: #get3pauthorizationurls

[16]: #getauthtype

[17]: #getoauthservice

[18]: #isauthvalid

[19]: #resetauth

[20]: #utils

[21]: #buildrows

[22]: #parameters-4

[23]: #deriveschema

[24]: #parameters-5

[25]: #requestpco

[26]: #parameters-6

[27]: https://developers.google.com/datastudio/connector/reference#getconfig

[28]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Object

[29]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/Boolean

[30]: https://developers.google.com/apps-script/reference/script/authorization-info

[31]: https://developer.mozilla.org/docs/Web/JavaScript/Reference/Global_Objects/String
