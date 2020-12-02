# bd-fp-splunk-app
Splunk Forcepoint App

## Package

```bash
./build/create-deployment.sh
```

## Implementation

```bash
sudo tar -zxvf fp-splunk-app-v1.tar.gz -C /opt/
```

### Log in as the user account running Splunk Enterprise processes.

```bash
cp -r /opt/fp-splunk-app/forcepoint-solutions $SPLUNK_HOME/etc/apps/
```

```bash
$SPLUNK_HOME/bin/splunk restart
```
