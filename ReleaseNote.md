<html>
<body>

<head>
    <meta charset="UTF-8">
    <title>CloudBudget2.0 Release Note</title>
</head>

<h1 id='pageTop'>CloudBudget2.0 Summer 2020 Release Note</h1>
<div>
    <p>List of Summer 2020 additives</p>

    <ul>
        <li><a href="ReleaseNote.html#budgetApp">Budget Application</a></li>
        <li><a href="ReleaseNote.html#budgetAppSheet">Budget App Sheet</a></li>
        <li><a href="ReleaseNote.html#googleDrive">Google Drive</a></li>
        <li><a href="ReleaseNote.html#PostingRules">Posting Rules</a></li>
        <li><a href="ReleaseNote.html#CBalances">CBalances</a></li>
        <li><a href="ReleaseNote.html#CBReports">CB Reports</a></li>
        <li><a href="ReleaseNote.html#reportConfigurator">Report Configurator</a></li>
        <li><a href="ReleaseNote.html#FFIntegration">FF Integration</a></li>
        <li><a href="ReleaseNote.html#other">Other</a></li>
    </ul>
    <p>You can find additional information for each item below.</p>

    <br/>
    <hr/>

    <br/>
    <h3 id='budgetApp'>Budget App</h3>
    <ul>
        <li>Autocomplete panel allows to enter a value more conveniently</li>
        <li>Excel import recognizes cell formulas</li>
        <li>Advanced capabilities of Calculation rules</li>
        <li>Currency component allows to work with Budget App using the user's currency</li>
        <li>Budget App has both modes: Employee/Rate & Price/Quantity</li>
    </ul>
    <br/>
    <img src="images/NRS2020BA.png" alt="Budget App Autofill" class="inline"/>
    <br/><br/>


    <h3 id='budgetAppSheet'>Budget App Sheet</h3>
    <ul>
        <li>Grouping by Accounts, SubAccounts, client analytics with and without Budget Apps</li>
        <li>New Excel export format (each Budget App on its own sheet)</li>
        <li>Currency component allows to work with Budget App using the user's currency</li>
        <li>Budget App has both modes: Employee/Rate & Price/Quantity</li>
    </ul>
    <br/>
    <br/><br/>

    <h3 id='googleDrive'>Google Drive</h3>
    <ul>
        <li>Grouping by Accounts, SubAccounts, client analytics with and without Budget Apps</li>
        <li>New Excel export format (each Budget App on its own sheet)</li>
        <li>Currency component allows to work with Budget App using the user's currency</li>
        <li>Budget App has both modes: Employee/Rate & Price/Quantity</li>
    </ul>
    <br/>
    <br/><br/>


</div>
<br/>


<br/>
<hr/>
<div>
    Navigate to:
    <p><a href="https://cloudbudgetinc.github.io/Docs/CBCore">CB Base Documentation</a></p>
</div>

<button onclick="topFunction()" id="myBtn" title="Go to top">Top</button>

<script>
    let mybutton = document.getElementById("myBtn");
    window.onscroll = function () {
        scrollFunction()
    };

    function scrollFunction() {
        mybutton.style.display = document.body.scrollTop > 20 || document.documentElement.scrollTop > 20 ? "block" : "none";
    }

    function topFunction() {
        document.body.scrollTop = 0;
        document.documentElement.scrollTop = 0;
    }
</script>

<style>
    #myBtn {
        display: none;
        position: fixed;
        bottom: 20px;
        right: 30px;
        z-index: 99;
        font-size: 18px;
        border: 1px solid #b5e853;
        outline: none;
        background-color: #171717;
        color: #b5e853;
        cursor: pointer;
        padding: 15px;
        border-radius: 4px;
    }

    #myBtn:hover {
        background-color: #181818;
    }
</style>


</body>
</html>