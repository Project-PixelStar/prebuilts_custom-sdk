# prebuilts/custom-sdk

## Run script

### Manually build `pom2bp`

```bash
sudo apt install -y golang
cd build/soong/cmd/pom2bp
go build pom2bp.go
```

move `pom2bp` binary to desired location.
Should be included `$PATH` (e.g. `~/.local/bin`).

### Install `six` with `pip3`

```python
pip3 install six
```

### Execute

```python
python3 update_prebuilts.py
```
