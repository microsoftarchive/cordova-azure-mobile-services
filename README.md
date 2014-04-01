Apache Cordova plugin for Windows Azure Mobile Services
=============================

Exposes JavaScript api to access a mobile services instance from an Apache Cordova app. The plugin includes the following objects:

  * [MobileServiceClient](http://msdn.microsoft.com/en-us/library/windowsazure/jj554219.aspx)

  * [MobileServiceTable](http://msdn.microsoft.com/en-us/library/windowsazure/jj554239.aspx)

To learn more about **Windows Azure Mobile Services**, visit [Developer Center](http://www.windowsazure.com/en-us/develop/mobile).

### Sample usage ###
The following code creates a new client object to access the *todolist* mobile service and create a new proxy object for the *TodoItem* table.

    var mobileService = new WindowsAzure.MobileServiceClient(
            "https://todolist.azure-mobile.net",
            "XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
        );

    var todoTable = mobileService.getTable('TodoItem');

### Copyrights ###
Copyright (c) Microsoft Open Technologies, Inc. All rights reserved.

Licensed under the Apache License, Version 2.0 (the "License"); you may not use these files except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
