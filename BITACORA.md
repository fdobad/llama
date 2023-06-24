# BITACORA

    git git remote set-url origin git@github.com:fdo/llama.git
    python -m venv ~/pyenv/llama
    pip install -r requirements.txt
    ./download.sh 

        Downloading tokenizer
        HTTP request sent, awaiting response... 200 OK
        Length: 499723 (488K) [binary/octet-stream]
        Saving to: ‘models/tokenizer.model’

        models/tokenizer.model                100%[========================================================================>] 488.01K   687KB/s    in 0.7s    

        2023-06-24 14:03:14 (687 KB/s) - ‘models/tokenizer.model’ saved [499723/499723]

        HTTP request sent, awaiting response... 200 OK
        Length: 50 [binary/octet-stream]
        Saving to: ‘models/tokenizer_checklist.chk’

        models/tokenizer_checklist.chk        100%[========================================================================>]      50  --.-KB/s    in 0s      

        2023-06-24 14:03:15 (1.09 MB/s) - ‘models/tokenizer_checklist.chk’ saved [50/50]

        tokenizer.model: OK
        Downloading 7B
        HTTP request sent, awaiting response... 200 OK
        Length: 13476939516 (13G) [binary/octet-stream]
        Saving to: ‘models/7B/consolidated.00.pth’

        models/7B/consolidated.00.pth         100%[========================================================================>]  12.55G  11.1MB/s    in 19m 55s 

        2023-06-24 14:23:12 (10.8 MB/s) - ‘models/7B/consolidated.00.pth’ saved [13476939516/13476939516]

        HTTP request sent, awaiting response... 200 OK
        Length: 101 [application/json]
        Saving to: ‘models/7B/params.json’

        models/7B/params.json                 100%[========================================================================>]     101  --.-KB/s    in 0s      

        2023-06-24 14:23:13 (1.32 MB/s) - ‘models/7B/params.json’ saved [101/101]

        HTTP request sent, awaiting response... 200 OK
        Length: 100 [binary/octet-stream]
        Saving to: ‘models/7B/checklist.chk’

        models/7B/checklist.chk               100%[========================================================================>]     100  --.-KB/s    in 0s      

        2023-06-24 14:23:14 (1.78 MB/s) - ‘models/7B/checklist.chk’ saved [100/100]

        Checking checksums
        consolidated.00.pth: OK
        params.json: OK
