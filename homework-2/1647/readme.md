### 运行节点
#### 执行命令
```bash
[root@Alan-PC substrate-node]# ./solochain-template-node --dev --tmp
2024-12-09 12:25:26 Substrate Node    
2024-12-09 12:25:26 ✌️  version 0.0.0-308ec258b0c    
2024-12-09 12:25:26 ❤️  by Parity Technologies <admin@parity.io>, 2017-2024    
2024-12-09 12:25:26 📋 Chain specification: Development    
2024-12-09 12:25:26 🏷  Node name: afraid-stranger-6491    
2024-12-09 12:25:26 👤 Role: AUTHORITY    
2024-12-09 12:25:26 💾 Database: RocksDb at /tmp/substratetAlFlV/chains/dev/db/full    
2024-12-09 12:25:27 🔨 Initializing Genesis block/state (state: 0x8c4d…9f59, header-hash: 0x8dd6…e493)    
2024-12-09 12:25:27 👴 Loading GRANDPA authority set from genesis on what appears to be first startup.    
2024-12-09 12:25:27 Using default protocol ID "sup" because none is configured in the chain specs    
2024-12-09 12:25:27 🏷  Local node identity is: 12D3KooWMbb5EDzbYLA8DLFNmzTvjQVr1tEaS2b77WQKSkJFkmfb    
2024-12-09 12:25:27 💻 Operating system: linux    
2024-12-09 12:25:27 💻 CPU architecture: x86_64    
2024-12-09 12:25:27 💻 Target environment: gnu    
2024-12-09 12:25:27 💻 CPU: AMD Ryzen 7 6800H with Radeon Graphics    
2024-12-09 12:25:27 💻 CPU cores: 2    
2024-12-09 12:25:27 💻 Memory: 3920MB    
2024-12-09 12:25:27 💻 Kernel: 5.15.167.4-microsoft-standard-WSL2    
2024-12-09 12:25:27 💻 Linux distribution: Fedora Linux 40 (Container Image)    
2024-12-09 12:25:27 💻 Virtual machine: yes    
2024-12-09 12:25:27 📦 Highest known block at #0    
2024-12-09 12:25:27 〽️ Prometheus exporter started at 127.0.0.1:9615    
2024-12-09 12:25:27 Running JSON-RPC server: addr=127.0.0.1:46604, allowed origins=["*"]    
2024-12-09 12:25:30 🙌 Starting consensus session on top of parent 0x8dd69fc05f695a3a00c5d7de1f2e25e1d352a66d0368fecb1cf6e5c727b4e493    
2024-12-09 12:25:30 🎁 Prepared block for proposing at 1 (1 ms) [hash: 0x32302c23a7b2329bd6d1d25a83309580e8a128b816e43618dce9d1905eace01e; parent_hash: 0x8dd6…e493; extrinsics (1): [0x15bd…3361]    
2024-12-09 12:25:30 🔖 Pre-sealed block for proposal at 1. Hash now 0x4df5d913eeca8c7c24ae7310fce87696fd2b3e103224d49ab5dc95f699dcef38, previously 0x32302c23a7b2329bd6d1d25a83309580e8a128b816e43618dce9d1905eace01e.    
2024-12-09 12:25:30 ✨ Imported #1 (0x4df5…ef38)    
2024-12-09 12:25:32 💤 Idle (0 peers), best: #1 (0x4df5…ef38), finalized #0 (0x8dd6…e493), ⬇ 0 ⬆ 0    
2024-12-09 12:25:36 🙌 Starting consensus session on top of parent 0x4df5d913eeca8c7c24ae7310fce87696fd2b3e103224d49ab5dc95f699dcef38    
2024-12-09 12:25:36 🎁 Prepared block for proposing at 2 (0 ms) [hash: 0x92b71047d981027e05b3d94d83b37a62cf0c6080989d2424444f437f8220370c; parent_hash: 0x4df5…ef38; extrinsics (1): [0x693b…1bcb]    
2024-12-09 12:25:36 🔖 Pre-sealed block for proposal at 2. Hash now 0x57af6a43d2b5e9658c0eea053f3055b2b4c4d274c64fad44b489ab808c3303ec, previously 0x92b71047d981027e05b3d94d83b37a62cf0c6080989d2424444f437f8220370c.    
2024-12-09 12:25:36 ✨ Imported #2 (0x57af…03ec)    
2024-12-09 12:25:37 💤 Idle (0 peers), best: #2 (0x57af…03ec), finalized #0 (0x8dd6…e493), ⬇ 0 ⬆ 0    
2024-12-09 12:25:42 🙌 Starting consensus session on top of parent 0x57af6a43d2b5e9658c0eea053f3055b2b4c4d274c64fad44b489ab808c3303ec    
2024-12-09 12:25:42 🎁 Prepared block for proposing at 3 (1 ms) [hash: 0xab12d47577385510a0b02d94a291d2eef5377ccd0f73d177771fafc68850f998; parent_hash: 0x57af…03ec; extrinsics (1): [0x81ad…af7d]    
2024-12-09 12:25:42 🔖 Pre-sealed block for proposal at 3. Hash now 0x3be265a893018f9804935a0a74bd6992ea57cb314798258ca7f5444e77eb9eb6, previously 0xab12d47577385510a0b02d94a291d2eef5377ccd0f73d177771fafc68850f998.    
2024-12-09 12:25:42 ✨ Imported #3 (0x3be2…9eb6)    
2024-12-09 12:25:42 💤 Idle (0 peers), best: #3 (0x3be2…9eb6), finalized #0 (0x8dd6…e493), ⬇ 0 ⬆ 0    
2024-12-09 12:25:47 💤 Idle (0 peers), best: #3 (0x3be2…9eb6), finalized #1 (0x4df5…ef38), ⬇ 0 ⬆ 0    
2024-12-09 12:25:48 🙌 Starting consensus session on top of parent 0x3be265a893018f9804935a0a74bd6992ea57cb314798258ca7f5444e77eb9eb6    
2024-12-09 12:25:48 🎁 Prepared block for proposing at 4 (1 ms) [hash: 0xc5748bc73f4dff35d94c228ae03360280cb0d9ed297cb6f3e611ab4e13ef2c16; parent_hash: 0x3be2…9eb6; extrinsics (1): [0xe2d8…95df]    
2024-12-09 12:25:48 🔖 Pre-sealed block for proposal at 4. Hash now 0xb47aea93605536fd35fe3a6c88d963f0fbde0c9f50e4caef0a7f20a4e0dc13d3, previously 0xc5748bc73f4dff35d94c228ae03360280cb0d9ed297cb6f3e611ab4e13ef2c16.    
2024-12-09 12:25:48 ✨ Imported #4 (0xb47a…13d3)    
2024-12-09 12:25:52 💤 Idle (0 peers), best: #4 (0xb47a…13d3), finalized #2 (0x57af…03ec), ⬇ 0 ⬆ 0    
2024-12-09 12:25:54 🙌 Starting consensus session on top of parent 0xb47aea93605536fd35fe3a6c88d963f0fbde0c9f50e4caef0a7f20a4e0dc13d3    
2024-12-09 12:25:54 🎁 Prepared block for proposing at 5 (0 ms) [hash: 0xeeba48263772736a2c78e58153284a2ee950ce963573b65dd473d95abafe58a7; parent_hash: 0xb47a…13d3; extrinsics (1): [0x1dc6…8c6e]    
2024-12-09 12:25:54 🔖 Pre-sealed block for proposal at 5. Hash now 0xf05fb5ec9c6d346b30ad8a5637110166da864dd571cfc820e1a7c979b669ae9c, previously 0xeeba48263772736a2c78e58153284a2ee950ce963573b65dd473d95abafe58a7.    
2024-12-09 12:25:54 ✨ Imported #5 (0xf05f…ae9c)    
2024-12-09 12:25:57 💤 Idle (0 peers), best: #5 (0xf05f…ae9c), finalized #3 (0x3be2…9eb6), ⬇ 0 ⬆ 0    
2024-12-09 12:26:00 🙌 Starting consensus session on top of parent 0xf05fb5ec9c6d346b30ad8a5637110166da864dd571cfc820e1a7c979b669ae9c    
2024-12-09 12:26:00 🎁 Prepared block for proposing at 6 (0 ms) [hash: 0xe89b1b007a4a193919ba4899fd9b243991dc13f0562778ff36e98e0301de80a6; parent_hash: 0xf05f…ae9c; extrinsics (1): [0xc6fd…d487]    
2024-12-09 12:26:00 🔖 Pre-sealed block for proposal at 6. Hash now 0x2e99a8f5b1ec316311892be9da95adfb124e54e68777cf44fd2ffc109141bb6d, previously 0xe89b1b007a4a193919ba4899fd9b243991dc13f0562778ff36e98e0301de80a6.    
2024-12-09 12:26:00 ✨ Imported #6 (0x2e99…bb6d)    
```
#### 运行截图
![image](https://github.com/user-attachments/assets/cc8edd7f-41d4-4dea-9aa2-53532f72d457)
