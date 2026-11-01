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
