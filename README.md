# comp5461-assignment-1-client-server-application-solved
**TO GET THIS SOLUTION VISIT:** [COMP5461 Assignment 1-Client-Server-Application Solved](https://www.ankitcodinghub.com/product/comp5461-assignment-1-client-server-application-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;100018&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP5461 Assignment 1-Client-Server-Application Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Problem specification.

In a client-server system, the client application sends requests to a server application through a network connection. In such system, the user interface is implemented in the client and the database is stored in the server.

You are required to implement a client-server application to process banking transactions such as withdrawals and deposits. In modern banking systems, a costumer accesses a bank account using an access card at an ATM, at the counter or on the web.

• Implementation.

The following diagram illustrates the classes for the client-server banking

application.

</div>
</div>
<div class="layoutArea">
<div class="column">
Main class

</div>
</div>
<div class="layoutArea">
<div class="column">
Client class

</div>
</div>
<div class="layoutArea">
<div class="column">
Server class

</div>
</div>
<div class="layoutArea">
<div class="column">
Network class

</div>
</div>
<div class="layoutArea">
<div class="column">
Transactions class

</div>
</div>
<div class="layoutArea">
<div class="column">
Accounts class

</div>
</div>
<div class="layoutArea">
<div class="column">
Winter 2021 Page 1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
▪ Network class.

</div>
</div>
<div class="layoutArea">
<div class="column">
The Network class provides the infrastructure to allow the client and the server to process the transactions. The client and the server need to be connected (using connect()) to the network prior to an exchange. The Network class also implements an input buffer (inComingPacket[]) and an output buffer (outGoingPacket[]) to respectively receive transactions from the client and to return updated transactions to the client. The capacity of these buffers are 10 elements, so the network indicates whether they are full or empty.

<ul>
<li>▪ &nbsp;Client class.
The Client class reads all the transactions from a file (transaction.txt) and saves them in an array (transaction[]). A transaction is implemented by the Transactions.class.

Using the send() method of Network class the client transfers the transactions to the network input buffer and it yields the cpu in case the network input buffer is full.

Also, using the receive() method of Network class the client retrieves the updated transactions from the network output buffer and yields the cpu in case the buffer is empty. Each updated transaction received is displayed immediately on the console.
</li>
<li>▪ &nbsp;Server class.
The Server class reads all the accounts from a file (account.txt) and saves them in an array (account[]). An account is implemented by the Accounts class. Using the transferrIn() method of Network class the server retrieves the transactions from the network input buffer and performs the operations (withdraw, deposit, query) on the specific accounts. It yields the cpu in case the buffer is empty.

Each updated transaction is transmitted to the network output buffer using the transferOut( ) method of Network class and the server yields the cpu in case the buffer is full.

• Problems.
</li>
</ul>
▪ You need to complete the Java program that is provided by implementing 4 threads so that the client, the server and the network all run concurrently. The client has 2 threads, one for sending the transactions and another for receiving the completed transactions.

In case the input and output network buffers are full or empty each client or server thread must yield the cpu using the Java method Thread.yield(). The network thread executes an infinite loop that ends when both client and server threads have disconnected. In case the client or sever threads are still connected the network thread must continuously yield the cpu.

</div>
</div>
<div class="layoutArea">
<div class="column">
Winter 2021 Page 2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ul>
<li>▪ &nbsp;You must record the running times of both client threads and the server thread using the Java method System.currentTimeMillis().</li>
<li>▪ &nbsp;You need to provide output test cases with the appropriate running times for the client and the server threads. Perform 3 different runs of the program and explain why there is a difference in the running times.</li>
</ul>
• Sample output test cases.

▪ See attached text files.

• Evaluation.

You will be evaluated mostly on the implementation of the required methods, the

</div>
</div>
<div class="layoutArea">
<div class="column">
implementation of the threads, the measurements sharing of the cpu by the threads.

▪ Evaluation criteria

Implementation of the 4 threads Implementation of the main class Answer to a question during the demo

Implementation of the yield( ) method

Implementation of the measurements of the running times

Output test cases including running times

• Required documents.

</div>
<div class="column">
of the running times and the voluntary

35% 15% 10%

10% 10% 20%

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Criteria

</div>
</div>
</td>
<td>
<div class="layoutArea">
<div class="column">
Marks

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
<ul>
<li>▪ &nbsp;Source codes in Java.</li>
<li>▪ &nbsp;Output test cases.</li>
<li>▪ &nbsp;I have included DEBUG flags in the source code in order to help you trace the
program but once your program works properly you should put the DEBUG flags in comments.

• Submission.
</li>
</ul>
▪ Create one zip file, containing the necessary files (.java, .txt and test cases). If the assignment is done individually, your file should be called pa1_studentID, where pa1 is the number of the assignment and studentID is your student ID number. If the work is done in a team of 2 people, the zip file should be called pa1_studentID1_studentID2 where studentID1 and studentID2 are the student ID numbers of each student.

</div>
</div>
<div class="layoutArea">
<div class="column">
Winter 2021 Page 3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
▪ Upload your zip file on moodle under Programming Assignment 1 before the due date.

• IMPORTANT (Please read very carefully):

A demo will take place with the markers afterwards. Markers will inform you about the details of demo time and how to book a time slot for your demo. If working in a group, both members must be present during demo time. Different marks may be assigned to teammates based on this demo.

<ul>
<li>▪ &nbsp;If you fail to demo, a zero mark is assigned regardless of your submission.</li>
<li>▪ &nbsp;If you book a demo time, and do not show up, for whatever reason, you will be
allowed to reschedule a second demo but a penalty of 50% will be applied.
</li>
<li>▪ &nbsp;Failing to demo at the second appointment will result in zero marks and no more
chances will be given under any conditions.

• Disclaimer.

▪ Note that this code has been tested on Windows. You may need to make changes if you would like to run on other OS. However, you are not permitted to change the implementation of the source code provided nor change the data types and sizes but you should only implement the features as required.
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
Winter 2021 Page 4

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
Account

</div>
</div>
<div class="layoutArea">
<div class="column">
• Detailed implementation of the classes NETWORK

</div>
</div>
<div class="layoutArea">
<div class="column">
SERVER

</div>
</div>
<div class="layoutArea">
<div class="column">
Out Buffer

</div>
</div>
<div class="layoutArea">
<div class="column">
In Buffer

</div>
</div>
<div class="layoutArea">
<div class="column">
CLIENT

</div>
</div>
<div class="layoutArea">
<div class="column">
▪ Client class

</div>
</div>
<div class="layoutArea">
<div class="column">
-send() -receive() -transferIn() -transferout()

</div>
</div>
<div class="layoutArea">
<div class="column">
Client

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>– &nbsp;numberOfTransactions : int /* total number of transactions to process */</li>
<li>– &nbsp;maxNbTransactions : int /* maximum number of transactions */</li>
<li>– &nbsp;transactions : Transactions[ ] /* transaction array */</li>
<li>– &nbsp;clientOperation : String /* sending, receiving */</li>
<li>– &nbsp;objNetwork : Network /* handle to access network methods */</li>
</ul>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Client(String operation) +getNumberOfTransactions( ) : int +getClientOperation() : String +setNumberOfTransactions(int nbOfTrans) : void +setClientOperation(String operation) : void +readTransactions( ) : void

+sendTransactions( ) : void +receiveTransactions(Transactions transact) : void +toString( ) : String

+run() : void

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Winter 2021

</div>
<div class="column">
Page 5

</div>
</div>
<div class="layoutArea">
<div class="column">
▪

</div>
</div>
<div class="layoutArea">
<div class="column">
Transaction

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
▪ Transactions class

</div>
</div>
<div class="layoutArea">
<div class="column">
Transactions

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>– &nbsp;accountNumber : String /* account number */</li>
<li>– &nbsp;operationType : String /* deposit, withdrawal, query */</li>
<li>– &nbsp;transactionAmount : double /* transaction amount */</li>
<li>– &nbsp;transactionBalance : double /* updated account balance */</li>
<li>– &nbsp;transactionError : String /* NSF, invalid amount or account, none */</li>
<li>– &nbsp;transactionStatus : String /* pending, sent, received, done */</li>
</ul>
</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Transactions( )

+ getTransactionType( ) : String

+ getAccountNumber( ) : String

+ getTransactionAmount( ) : double

+ getTransactionBalance( ) : double

+ getTransactionError( ) : String

+ getTransactionStatus( ) : String

+ setAccountNumber(String accNumber ) : void

+ setTransactionType(String opType) : void

+ setTransactionAmount(double transAmount ) : void + setTransactionBalance(double transBalance ) : void + setTransactionError(String transError) : void

+ setTransactionStatus(String transStatus) : void

+ toString( ) : String

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
▪ Server class

</div>
</div>
<div class="layoutArea">
<div class="column">
Server

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
– numberOfTransactions : int /* total number of transactions received */

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>– &nbsp;numberOfAccounts : int</li>
<li>– &nbsp;maxNbAccounts : int</li>
<li>– &nbsp;transaction : Transactions</li>
<li>– &nbsp;objNetwork : Network</li>
<li>– &nbsp;account : Accounts[]</li>
</ul>
</div>
<div class="column">
/* total number of accounts saved */ /* maximum number of accounts */ /* a transaction to process */

/ * handle to access network methods */ /* account array */

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Server( )

+getNumberOfTransactions( ) : int +getNumberOfAccounts( ) : int +getMaxNbAccounts() : int +setNumberOfTransactions(int nbOfTrans) : void +setNumberOfAccounts(int nbOfAcc) : void +setMaxNbAccounts(int nbOfAcc) :void +initializeAccounts( ) : void

+findAccount(String accNumber) : int +processTransactions(Transaction trans) : boolean +deposit(int i, double amount) : double +withdraw(int i, double amount) : double +query(int i) : double

+toString( ) : String

+run() : void

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Winter 2021

</div>
<div class="column">
Page 6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
▪ Accounts class

</div>
</div>
<div class="layoutArea">
<div class="column">
Accounts

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>– &nbsp;accountNumber : String</li>
<li>– &nbsp;accountType : String</li>
<li>– &nbsp;firstName : String</li>
<li>– &nbsp;lastName : String</li>
<li>– &nbsp;balance : double</li>
</ul>
</div>
<div class="column">
/* unique account number */

/* chequing, saving, credit */

/* first name of account holder */

/* last name of account holder */ /* account balance */

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
+ getAccountNumber( ) : String + getAccountType( ) : String

+ getFirstName( ) : String

+ getLastname( ) : String

+ getBalance( ) : double

+ setAccountNumber(double accNumber) : void + setAccountType(String accType) : void

+ setFirstName(String fName) : void

+ setLastname(String lName) : void

+ setBalance(double bal) : void

+ toString( ) : String

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
▪ Network class

</div>
</div>
<div class="layoutArea">
<div class="column">
Network

</div>
</div>
<table>
<tbody>
<tr>
<td>
<div class="layoutArea">
<div class="column">
<ul>
<li>– &nbsp;clientIP : string</li>
<li>– &nbsp;serverIP : string</li>
<li>– &nbsp;portID : int</li>
<li>– &nbsp;clientConnectionStatus : String</li>
<li>– &nbsp;serverConnectionStatus : String</li>
<li>– &nbsp;maxNbPackets : int</li>
</ul>
</div>
<div class="column">
/* IP of client application */

/* IP of server application */

/* port ID of client application */ /* connected, disconnected */

/* connected, disconnected */

/* capacity of network buffers */ /* network input buffer */

/* network output buffer */

</div>
</div>
<div class="layoutArea">
<div class="column">
<ul>
<li>– &nbsp;inComingPacket : Transactions[10]</li>
<li>– &nbsp;outGoingPacket : Transactions[10]</li>
<li>– &nbsp;inBufferStatus, outBufferStatus : String /* normal, full, empty */</li>
<li>– &nbsp;inputIndexClient, inputIndexServer, outputIndexServer, outputIndexClient :</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
int /* buffer index position */

– networkStatus : String /* active, inactive */

</div>
</div>
</td>
</tr>
<tr>
<td>
<div class="layoutArea">
<div class="column">
Network(String context) + getClientIP( ) : String

+ getServerIP( ) : String

+ getPortID( ) : integer

+ getClientConnectionStatus( ) : String + getServerConnectionStatus( ) : String + getInBufferStatus( ) : string

+ getOutBufferStatus( ) : string

+ getNetworkStatus( ) : String + getInputIndexClient( ) : int

+ getInputIndexServer( ) : int

+ getIOutputIndexClient( ) : int + getOutputIndexServer( ) : int + setClientIP(String cip) : void + setServerIP(String sip) : void

</div>
</div>
</td>
</tr>
</tbody>
</table>
<div class="layoutArea">
<div class="column">
Winter 2021

</div>
<div class="column">
Page 7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="section">
<div class="layoutArea">
<div class="column">
+ setPortID(int pid) : void

+ setClientConnectionStatus(String connectStatus) : void + setServerConnectionStatus(String connectStatus) : void + setNetworkStatus(String netStatus ) : void

+ setInBufferStatus(String inBufStatus) : void

+ setOutBufferStatus(String outBufStatus) : void

+ setInputIndexClient(int i1) : void

+ setInputIndexServer(int i2) : void

+ setOutputIndexClient(int o2) : void

+ setOutputIndexServer(int o1) : void

+ connect(String IP) : boolean

+ disconnect(String IP) : boolean

+ send(Transactions inPacket ) : boolean

+ receive(Transactions outPacket) : boolean

+ transferOut(Transactions outPacket ) : boolean

+ transferIn(Transactions inPacket) : boolean

+ toString( ) : String

+run() : void

</div>
</div>
</div>
<div class="layoutArea">
<div class="column">
Winter 2021 Page 8

</div>
</div>
</div>
