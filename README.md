

# Film_Translation

## How to use this? 
### Requirements

* Python (>= 2.7)
* TensorFlow (>= 1.4)

### Installation

https://drive.google.com/file/d/1OKnYmWHozlJhcK-VZ16KszENUuWMd1kM/view?usp=sharing \
The Folder was too heavy to import it on Github, so please download it from the link above and unzip it. 

```bash
$pip install OpenNMT-tf
$cd Film_Translation 
# This command makes a translation for each sentence from src-test.txt and prints
# Score || Translation
$onmt-main score --config config/opennmt-defaults.yml config/data/toy-ende.yml --features_file data/toy-ende/src-test.txt --predictions_file data/toy-ende/tgt-test.txt
```

### Resources
MIT's Open source neural machine translation system \
http://opennmt.net/
