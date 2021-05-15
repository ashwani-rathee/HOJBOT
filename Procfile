web: pip install -r requirements.txt
web: julia --project=. -e 'using Pkg; Pkg.instantiate()'
web: ENABLE_WARM_UP=0 script/run.sh
