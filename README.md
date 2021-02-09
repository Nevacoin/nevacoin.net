The first decentralized cryptocurrency ever to be created as a gift for someone's birthday. At 1457344680 unix time is my girlfriend's 25th birthday (her name is Neva if that isn't obvious) and since she is abroad at the moment I figured this is the best gift I can give her remotely. Who wouldn't want a global decentralized peer to peer network cryptocurrency platform named after them as a birthday gift, right? Don't worry, I will also give her a less geeky gift when she comes back Smiley

Code: const char* pszTimestamp = "Happy 25th birthday Neva!!!"; genesis.nTime    = 1457344680;
      

The coin was successfully launched on March 7th, 9:58AM (GMT) and is available for mining (for the next 14years) and staking since day one.

Name meaning:

Gender: F  Meaning of Neva: "white snow" Origin of Neva: Spanish


What is the purpose of this coin?

- 0% PoS, fixed block rewards ensure predictable supply increase.

- Unlike most of PoW/PoS Hybrids, this one will have a very long PoW phase. The network will stop accepting PoW blocks in approximately 14 years. The goal is to gain a mining chance, even to people that stumble upon it years later in the future.

- Gain some interest from the female half of the population (starting with Neva). Lets be honest the cryptocurrency community is still a sausage fest Smiley

- Blake2s mining algorithm.

- Blake2s PoS block hashing - friendly to low end hardware. Raspberry-Pi nodes...etc.

- Slow emmision. The PoW and PoS reward is 5 NEVAs. The reward will halve for both at block height 2628000. That is approximately 7 years until the first halving. After the second halving at block height 5256000 the PoW phase will be over, continued only by PoS with 1.25 NEVA reward, which will halve again in 2628000 blocks...etc.

- The low reward and long PoW phase is meant to avoid the insta-mine by handful of people.

Coin specifications:

Ticker:                       NEVA
Type:                         PoW/Pos2.0 hybrid
PoW algorithm:           Blake2s  (read more)
Difficulty retarget:       Every block
Block target:               91 seconds
Block reward:              5 NEVA  (both PoW and PoS have static rewards)
Max block size:            4MB
Coinbase maturity:      25 blocks
Block reward halving:   every 2628000 blocks (approx 7 years, probably less)
Last PoW block:           5256000 (in approx 14 years)
PoS start:                    from the first block
Minimum PoS age:        4 hours
Maximum PoS age:       no max (PoS 2.0)
Max coins:                   26 280 000 NEVAs (this amount will be reached at block 131400000, or in roughly 350 years)

Sum of the mining/staking schedule:

Halvig phase      Block Reward        New coins created    Total coins created     Approx Time (years)
0                       5                         13140000               13140000                  7
1                       2.5                      6570000                 19710000                  14
2                       1.25                    3285000                  22995000                  21
3                       0.625                  1642500                  24637500                  28
4                       0.3125                 821250                   25458750                  35
5                       0.15625               410625                   25869375                  42
6                       0.078125             205312.5                 26074687.5               49
7                       0.0390625            102656.25              26177343.75              56
8                       0.01953125          51328.125              26228671.88              63
9                       0.009765625        25664.0625            26254335.94              70
10                     0.0048828125      12832.03125           26267167.97              77
                 .                    .                      .
                 .                    .                      .
                 .                    .                      .


Network info:

P2P port: 7391
RPC port: 3791

Testnet P2P port: 17391
Testnet RPC port: 13791

Seed nodes are hard coded.

QT GUI Wallet Features:
-Integrated block explorer
-Two themes, default light theme and an optional funky dark theme

Daemon features:
-coockie authentication
   - You do not need the rpcuser/password parameters in the nevacoin.conf to run the daemon. You can still use them if you want, but if they are not provided an authentication cookie file will be generated in the .nevacoin directory and also deleted on shutdown. So one less thing you have to do if you want to run a headles node for staking.

Basic setup for daemon in nevacoin.conf file is:
Code:
daemon=1


https://freiexchange.com/market/NEVA/BTC
