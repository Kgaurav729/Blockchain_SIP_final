# Blockchain_SIP_final
1. run configuration client 1, client 2 and node 1 in pycharm
2. for node side click on http link-eg. Running on http://127.0.0.1:5001 (Press CTRL+C to quit)
3. for node side click on http link-eg. Running on  http://127.0.0.1:8081  and http:/127.0.0.1:8082(Press CTRL+C to quit)
4. new tabs will open on the default browser.
5. enter any virtual name ..if virtual name already exists it will not allow. 
6. the above process have to be done for both client1 and client2
7. right now both the clients will have 50 btc intially as balance given by admin
8.switch to the client1 tab and click on make transaction and fill the required details. false details will be automatically not get mined.
9. path and hash of transaction can be found in the public ledger.
10. after successfully transaction  block will be added to the chain with required number of transaction.
11. precautions while giving the path
	if path lenght is like this txpath: ["c6615e39d98c2d0e67b71f2035b844aaa212598513f040c31b939a0208dc43d5"] then while giving path only give -c6615e39d98c2d0e67b71f2035b844aaa212598513f040c31b939a0208dc43d5
	if path  length is like this txpath:[[ '53614a4a00df15271560238bc4c5936f5116da5e72dd498450e76bbb9c51a55e, false], 96d39bf572451d647e1cfcc3973040e318a9ffc1fec7e0610f16c94cc391680a']
		just give as path length input as [ '53614a4a00df15271560238bc4c5936f5116da5e72dd498450e76bbb9c51a55e, false], 96d39bf572451d647e1cfcc3973040e318a9ffc1fec7e0610f16c94cc391680a'

