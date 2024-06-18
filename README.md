# aligned-layer-proof

### Update machine
```
sudo apt update -y && sudo apt upgrade -y

curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/install_aligned.sh | bash
source /root/.bashrc

curl -L https://raw.githubusercontent.com/yetanotherco/aligned_layer/main/batcher/aligned/get_proof_test_files.sh | bash
```

### Run the code and wait status VERIFIED of tx
```
rm -rf ~/aligned_verification_data/ &&
aligned submit \
--proving_system SP1 \
--proof ~/.aligned/test_files/sp1_fibonacci.proof \
--vm_program ~/.aligned/test_files/sp1_fibonacci-elf \
--aligned_verification_data_path ~/aligned_verification_data \
--conn wss://batcher.alignedlayer.com
```

### Tweet the tx link with hasthtag #aligned and tag @alignedlayer.
### Copy thet tweet and send the testnet discord channel. 
Aligned Layer Discord : https://discord.gg/vYktc2cC

![image](https://github.com/kivancbeser/aligned-layer-proof/assets/16528400/e3d6afe1-2f6f-4be5-932f-9e41b1527858)

