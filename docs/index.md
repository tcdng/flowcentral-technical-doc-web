# Welcome to flowCentral Documentation
This documentation helps you to learn about the flowCentral platform features, supported technologies, architecture, and other specifics. Find out how to create applications with the available components, and you will do this quick and with less code, you will be able to automate processes and integration is also seamless.
## Getting Started
With flowCentral platform developers can rapidly create and deploy the applications needed by organizations to adapt quickly to changes in operating environment that are driven by new business opportunities and regulatory requirements.<br>
This guide shows some of the basic steps required to get started with the platform:
            <li><a href="#download-flowCentral">Download flowCentral</a></li>
            <li><a href="#deploy-flowCentral">Deploy flowCentral</a></li>
    <h6 id="download-flowCentral">1. Download FlowCentral</h6>
            <li>Go to the FlowCentral website <a href="https://www.flowcentraltechnologies.com">https://www.flowcentraltechnologies.com</a></li>
            <li>Click the Downloads option on the top menu bar</li>
            <li>Download the FlowCentral standard edition<br>
                <i class="note">You can click the download button below to download</i><br>
            <a href="http://backend.flowcentraltech.com/plain/resource/downloadpath?resource=flowcentralserver-standard-0.0.9-BETA-2.zip"><button class="download"><i class="fa fa-download"></i> Download</button></a>
            </li>
    <h6>2. Extract</h6>
        <li>Extract the downloaded zip file into a suitable folder
    <h6>3. Run</h6>
        <li>Run the excutable jar in command line</li>
        <li>The FlowCentral is up and running, you can see it located in port 8080</li>
    <h6>4. Launch</h6>
        <li>Launch on any supported browser using <strong>localhost:8080</strong></li>
    <h6>5. Login</h6>
        <li>Login with your login ID and password and click the Login button</li>
        <li>A page comes up for you to change the default password to your preferred password, click Change password when done.</li>
    <h6>6. Welcome to FlowCentral.</h6>
        <li>The sample dashboard page comes up once you login.</li>
        <li>By default, the FlowCentral instance is connected to an in-memory sql database, so you need to reconfigure the instance to connect to a persistent database.<br>
    <h6 id="deploy-flowCentral">7. Deploy flowCentral(Database)</h6>
        <strong class="note">NOTE: We will be using the Postgres SQL database for this tutorial.</strong></li>
        <ol>
            <li>Go to Postgres</li>
            <li>Create a database user. Click on Server and the Login/Group Roles</li>
            <li>Right click on Login/Group Roles, hover on Create, click the Login/Group Roles option</li>
            <li>Enter the name and password, and enable the can login option and save</li>
            <li>Create a database and assign all priviledges to use the create in previous step. Right click on Databases, hover on Create and choose the Database option</li>
            <li>Enter the Database name in General, go to security, click the <strong>+</strong> sign in front of Privileges, select your folder name as the Grantee, select <strong>ALL</strong> Privileges and save.</li>
            <li>The database has been created and it has no table or view</li>
        </ol>
    <h6>8. Stop Instance</h6>
        <li>Stop the FlowCentral instance</li>
    <h6>9. Deploy FlowCentral(instance)</h6>
        <li>Go to the extracted folder on your computer, you will notice an <strong>inst</strong> folder has been created, this is where the    platform stores its dependencies and configuration files
        </li>
        <li>Open the <strong>inst</strong>folder and then the <strong>conf</strong> folder, open the instance configuration file <strong>Unify</strong>(XML Document) in a prefered editor</li>
    <div class="notify">
        <div class="center-align"><strong>Tip:</strong>Watch this video tutorial for a detailed guide.</div>
    </div>
    <iframe src="https://www.youtube.com/embed/jmqvZBY4sQg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"></iframe>