# TenBy10AnkiGenAI
uses a prebuilt Gen AI model that populates a downloadable .csv file for ANKI with meaningful translations and example sentences so that a user can create flashcards fast.

# How to run notebook
1. Go to Cerebras and get free API key: https://www.cerebras.ai/pricing?utm_campaign=&utm_source=google&utm_medium=cpc&utm_term=cerebras&hsa_acc=7666604837&hsa_cam=22913298711&hsa_grp=182922878606&hsa_ad=770367348663&hsa_src=g&hsa_tgt=aud-2405077481245:kwd-1431184875346&hsa_kw=cerebras&hsa_mt=p&hsa_net=adwords&hsa_ver=3&gad_source=1&gad_campaignid=22913298711&gbraid=0AAAAA-1Vm3uB2DoYjht73_mOn8dghN8c9&gclid=CjwKCAiA0eTJBhBaEiwA-Pa-hSbOIf8xEtz13ZuSef-jCoje9CdVN6_THGeWDycsz0FBDlIHNhcBfRoCFJAQAvD_BwE
2. Then go Repo project directory on your environment, create a .env file, Paste in: MY_CEREBRAS_API_KEY = YOUR_CEREBRAS_API_KEY 
3. On the Repo project directory, open the Python notebook called "TenBy10.ipynb" and ctrl f: client = Cerebras(api_key=os.environ
4. Replace, with your .env variable: client = Cerebras(api_key=os.environ["YOUR_CEREBRAS_API_KEY"])
