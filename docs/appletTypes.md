# Applet Types
## <id="Manage-Entity-List-Applet">Manage Entity List Applet
This applet type manages the behaviour and presentation of an entity in the end user view. You get to customize your entity by assigning different features and characteristics to determine how your entity looks, what it does and all other things associated with it.
    An applet with its type property set to ‘Manage Entity List Applet’ will produce an end-user feature for managing a list of records in a table with an associated form for individual record operations such as view, update and delete.
    Properties
    <table>
        <tr>
            <th>Key</th>
            <th>Name</th>
            <th>Description</th>
        </tr>
        <tr>
            <td>page.alternateCaption</td>
            <td>Page Alternate Caption</td>
            <td>This replaces the default caption if set.</td>
        </tr>
        <tr>
            <td>page.alternateSubCaption</td>
            <td>Page Alternate Sub-caption</td>
            <td>This field is like an expantiation of the page alternative caption.</td>
        </tr>
        <tr>
            <td>searchTable</td>
            <td>Search Table</td>
            <td>This is a Long name component for the applet. It lets you associate an existing table to your applet</td>
        </tr>
        <tr>
            <td>searchTable.new</td>
            <td>Search New</td>
            <td>This gives </td>
        </tr>
        <tr>
            <td>searchTable.new.caption</td>
            <td>Search Add Caption</td>
            <td>This replace the default caption of the add button on the entity search page</td>
        </tr>
        <tr>
            <td>searchTable.new.multiselect.ref</td>
            <td>Search Add Multi-select Reference</td>
            <td>This field lets you add a reference from the list of available references. It is a drop down with the list of references from the repository.<br> <a href="reference.html">Check available references.</a></td>
        </tr>
        <tr>
            <td>searchTable.report</td>
            <td>Search Report</td>
            <td>This allows you to search the report for a particular one</td>
        </tr>
        <tr>
            <td>searchTable.quickFilter</td>
            <td>Search Quick Filter</td>
            <td>This allows you to search through the quick filter</td>
        </tr>
        <tr>
            <td>searchTable.actionFooter</td>
            <td>Action Footer</td>
            <td>This is an area at the bottom of the page containing actions</td>
        </tr>
        <tr>
            <td>searchTable.basicSearchOnly</td>
            <td>Basic Search Only</td>
            <td>This allows you to perform basic search only</td>
        </tr>
        <tr>
            <td>createForm</td>
            <td>Create Form</td>
            <td>This field creates a form and also has a long name value with studio as the application name</td>
        </tr>
        <tr>
            <td>createForm.new.caption</td>
            <td>Create Caption</td>
            <td>This field allows you to create a caption about an applet form</td>
        </tr>
        <tr>
            <td>createForm.new.policy</td>
            <td>Create Policy</td>
            <td>After a form is created this creates a policy (or select from the list of available policies) about the form that is bing created</td>
        </tr>
        <tr>
            <td>createForm.submit</td>
            <td>Create Form Submit</td>
            <td>This allows you to create a submit button for the form created</td>
        </tr>
        <tr>
            <td>createForm.submit.caption</td>
            <td>Form Submit Caption</td>
            <td>Caption for the submit button</td>
        </tr>
        <tr>
            <td>createForm.submit.policy</td>
            <td>Create Submit Policy</td>
            <td>Policy for form submitted</td>
        </tr>
        <tr>
            <td>createForm.submit.validate</td>
            <td>Create Validate on Submit</td>
            <td>It lets you know if form should be validated</td>
        </tr>
        <tr>
            <td>createForm.submit.workflow.channel</td>
            <td>Create Submit Workflow</td>
            <td></td>
        </tr>
        <tr>
            <td>createForm.submitnext</td>
            <td>Create Form Submit and Next</td>
            <td>It lets you know if submit and next should be visible</td>
        </tr>
        <tr>
            <td>createForm.submitnext.caption</td>
            <td>Form Submit and Next Caption</td>
            <td>Caption for the submit and next button</td>
        </tr>
        <tr>
            <td>createForm.submit.buttonhighlight</td>
            <td>Submit Button Highlight</td>
            <td>This highlights the submit button to make it obvious.</td>
        </tr>
        <tr>
            <td>createForm.submit.condition</td>
            <td>Create Submit Condition</td>
            <td>This configures the submit button to only submit based on some given conditions.</td>
        </tr>
        <tr>
            <td>createForm.save</td>
            <td>Form Save</td>
            <td>This allows the save button to be visible</td>
        </tr>
        <tr>
            <td>createForm.save.next</td>
            <td>Form Save and Next</td>
            <td>It lets you know if save and next button should be visible</td>
        </tr>
        <tr>
            <td>createForm.onCreate.state.policy</td>
            <td>On-create Form State Policy</td>
            <td>This field allows you to state the form policy to use when you create a form.</td>
        </tr>
        <tr>
            <td>createForm.save.close</td>
            <td>Form Save and Close</td>
            <td>This is a flag that controls the visibility of the save and close button. If true it makes the save and close button visible, otherwise it hides it.</td>
        </tr>
        <tr>
            <td>listingForm</td>
            <td>Listing Form</td>
            <td>This lists the forms available for this entity applet</td>
        </tr>
        <tr>
            <td>maintainForm</td>
            <td>Maintain Form</td>
            <td>This allows you to make changes after the form has been created</td>
        </tr>
        <tr>
            <td>maintainForm.update</td>
            <td>Form Update</td>
            <td>This allow you to update your form. A pop up message comes up to tell you if it was successful or not.</td>
        </tr>
        <tr>
            <td>maintainForm.update.policy</td>
            <td>Update Policy</td>
            <td>This field is a drop down that gives you access to update your policy when the need arise.</td>
        </tr>
        <tr>
            <td>maintainForm.update.condition</td>
            <td>Update Condition</td>
            <td>This allows an update to be made on existing conditions or adds a new condition to the list of conditions</td>
        </tr>
        <tr>
            <td>maintainForm.submit</td>
            <td>Update Form Submit</td>
            <td>This updates the form after submission</td>
        </tr>
        <tr>
            <td>maintainForm.submit.policy</td>
            <td>Update Submit Policy</td>
            <td>This updates the policy that has been submitted to another existing policy</td>
        </tr>
        <tr>
            <td>maintainForm.submit.validate</td>
            <td>Update Validate on Submit</td>
            <td>It updates and validates a form on submission</td>
        </tr>
        <tr>
            <td>maintainForm.submit.workflow.channel</td>
            <td>Update Submit Workflow</td>
            <td>This updates the Workflow that has been submitted</td>
        </tr>
        <tr>
            <td>maintainForm.submitnext</td>
            <td>Update Form Submit and Next</td>
            <td>This creates updates the form, submit it and goes to the next action</td>
        </tr>
        <tr>
            <td>maintainForm.submit.condition</td>
            <td>Update Submit Condition</td>
            <td>This updates the submit condition</td>
        </tr>
        <tr>
            <td>maintainForm.delete</td>
            <td>Form Delete</td>
            <td>This allows to delete an existing form</td>
        </tr>
        <tr>
            <td>maintainForm.delete.policy</td>
            <td>Delete Policy</td>
            <td>This allows to delete an existing policy</td>
        </tr>
        <tr>
            <td>maintainForm.delete.condition</td>
            <td>Delete Condition</td>
            <td>This allows to delete an existing condition</td>
        </tr>
        <tr>
            <td>maintainForm.attachments</td>
            <td>Form Attachments</td>
            <td></td>
        </tr>
        <tr>
            <td>maintainForm.saveas</td>
            <td>Form Save As</td>
            <td>This allows you to save your form with a new name and description</td>
        </tr>
        <tr>
            <td>maintainForm.saveas.policy</td>
            <td>Save As Policy</td>
            <td>This allows you to save your policy with a new name and description</td>
        </tr>
        <tr>
            <td>baseRestriction</td>
            <td>Base Restriction</td>
            <td>This restricts the form from certain configurations</td>
        </tr>
    </table>
## Manage Entity List Applet (Assignment)
Lorem ipsum dolor sit amet. Aut quia beatae ad rerum magni qui consectetur voluptatem aut distinctio saepe ut autem doloribus. A Quis reprehenderit At galisum delectus est dolor quae et quos quia non tempora odit id asperiores eius est tenetur assumenda. Et molestiae inventore ut fugit error hic repellendus totam aut facere nemo non autem provident qui rerum perspiciatis. Et minima aspernatur rem voluptates laudantium aut odio voluptates ab sunt corporis et sunt magni.
    Properties
    <table>
        <tr>
            <th>Key</th>
            <th>Name</th>
            <th>Description</th>
        </tr>
        <tr>
            <td>searchTable</td>
            <td>Search Table</td>
            <td>This is a Long name component for the applet. It lets you associate an existing table to your applet</td>
        </tr>
        <tr>
            <td>searchTable.edit</td>
            <td>Search Edit</td>
            <td></td>
        </tr>
        <tr>
            <td>assignmentPage</td>
            <td>Assignment Page</td>
            <td></td>
        </tr>
        <tr>
            <td>assignmentEntryTable</td>
            <td>Assingment Entry Table</td>
            <td></td>
        </tr>
        <tr>
            <td>assignmentEntryTable.policy</td>
            <td>Assingment Entry Table Policy</td>
            <td></td>
        </tr>
        <tr>
            <td>assignmentUpdatePolicy</td>
            <td>Assingment Update Policy</td>
            <td></td>
        </tr>
    </table>
## Manage Entity List Applet (Single Form)
## Headless Tabs Applet
## Create Entity Applet
## Create Entity Applet (Single Form)
## Task Execution Apple
## Data Import Applet
## Facade Applet
## Path in Window
## Path in Page