
## **Requirements for compiling and interacting with the Voting DApp:**

### **Operating System**:
Ubuntu 16.xx or higher 

### **Packages**: 
1. Open a terminal 
2. Run these commands to install git, nodejs, npm, and truffle framework
```
sudo apt-get install git
sudo apt install nodejs
sudo apt-get install npm
sudo apt-get install build-essential
sudo npm install -g truffle
```

### **Steps to compile and host the voting DApp**:
1. Open 3 new terminals in the project directory
2. In terminal 1, run the nodejs component
```
cd app/javascripts
node node.js
```
3. In terminal 2, run the virtual memory blockchain (ganache-cli)
```
./node_modules/.bin/ganache-cli
```
5. In terminal 3, we will compile and deploy the smart contracts, after we will host the DApp
```
truffle migrate
npm run dev
```

### **Interacting with the voting DApp**:
1. navigate to *localhost:8080* in your browser of choice


