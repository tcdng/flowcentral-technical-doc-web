# Applet
An applet is a small application within the flowCentral platform that is used to perform a specific task. You define and group one or more applets, each with its set of properties, to create an application. The properties you set for each applet determines how it is presented to the end-user, how it will behave and what it can be used for.<br>
In all applet definitions, the type property is the primary determinant. For instance, an applet with its type property set to ‘Manage Entity List Applet’ will produce an end-user feature for managing a list of records in a table with an associated form for individual record operations - view, update and delete. Other properties affect additional visual presentation and functional behavior based on the applet type.<b>
    Properties
        <table>
        <tr>
            <th>Name</th>
            <th>Type</th>
            <th>Description</th>
            <th>Requirement</th>
        </tr>
        <tr>
            <td>type</td>
            <td>AppletType</td>
            <td>This field determines the type of applet.</td>
            <td>Mandatory</td>
        </tr>
        <tr>
            <td>entity</td>
            <td>String</td>
            <td>The long name of the database entity associated with the applet</td>
            <td>Mandatory</td>
        </tr>
        <tr>
            <td>icon</td>
            <td>String</td>
            <td>The icon displayed at the menu for the applet.</td>
            <td>Optional</td>
        </tr>
        <tr>
            <td>routeToApplet</td>
            <td>String</td>
            <td>The long name of the applet that this applet routes to. It applies to the ‘Facade Applet’ type..</td>
            <td>Optional</td>
        </tr>
        <tr>
            <td>path</td>
            <td>String</td>
            <td>The resource path to a content page. It applies to the ‘Path in WIndow’ and ‘Path in Page’ applet types..</td>
            <td>Optional</td>
        </tr>
        <tr>
            <td>baseField</td>
            <td>String</td>
            <td>The name of the field that holds the primary key of the entity to be assigned to. It applies to ‘Manage Entity List (Assignment)’ applet type.</td>
            <td>Optional</td>
        </tr>
        <tr>
            <td>assignField</td>
            <td>String</td>
            <td>The name of the field that holds the primary key of the entity that is assigned. It applies to ‘Manage Entity List (Assignment)’ applet type.</td>
            <td>Optional</td>
        </tr>
        <tr>
            <td>assignDescField</td>
            <td>String</td>
            <td>The name of the field that holds the description of the entity that is assigned. It applies to ‘Manage Entity List (Assignment)’ applet type.</td>
            <td>Optional</td>
        </tr>
        <tr>
            <td>displayIndex</td>
            <td>int</td>
            <td>This is the order in which your applet is displayed usually in the menu. Defaults to zero..</td>
            <td>Optional</td>
        </tr>
        <tr>
            <td>menuAccess</td>
            <td>boolean</td>
            <td>This flag indicates that the applet should be visible at the end-user application menu.</td>
            <td>Mandatory</td>
        </tr>
    </table>
    Types
    Different types of applets are available for the developer. These applet types let the developers choose what applet they are creating.
    These applet types are:
        <ul>
            <li><a href="appletTypes.md#Manage-Entity-List-Applet">Manage Entity List Applet</a></li>
            <li><a href="manageEntityList(assignment).html">Manage Entity List Applet (Assignment)</a></li>
            <li><a href="manageEntityList(singleForm).html">Manage Entity List Applet (Single Form)</a></li>
            <li><a href="headlessTabsApplet.html">Headless Tabs Applet</a></li>
            <li><a href="createEntityApplet.html">Create Entity Applet</a></li>
            <li><a href="createEntityApplet(singleForm).html">Create Entity Applet (Single Form)</a></li>
            <li><a href="taskExecutionApplet.html">Task Execution Applet</a></li>
            <li><a href="dataImportApplet.html">Data Import Applet</a></li>
            <li><a href="facadeApplet.html">Facade Applet</a></li>
            <li><a href="pathInWindows.html">Path in Window</a></li>
            <li><a href="pathInPage.html">Path in Page</a></li>
        </ul>
    
##Applet Types
##Applet Filters
##Applet Properties