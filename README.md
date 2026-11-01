# toolforge-jobs

## Commands

Build venv
```
toolforge-jobs run bootstrap-venv --command "cd $PWD && ./bootstrap_venv.sh" --image python3.13 --wait
```

Load jobs
```
toolforge-jobs load toolforge-jobs.yaml
```

Run single job
```
toolforge-jobs run o1-deleter-once --command "bot/pyvenv/bin/python3 bot/o1-deleter/main.py" --image python3.13 --wait
```
