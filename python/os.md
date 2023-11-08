# Os

## Base
```python
# Change current working directory
os.chdir(<Path>)

# Return the folder list specified by <Path>
os.listdir(<Path>)

# Delete the file with path <Path>
os.remove(<Path>)

# Delete the empty folder specified by <Path>
os.rmdir(<Path>)

# Delete file path
os.unlink(<Path>)
```

## Path
```python
# Return absolute path
os.path.abspath(<Path>)

# Check if <Path> exists
os.path.exists(<Path)>

# Determine whether it is an absolute path
os.path.isabs(<Path>)

# Determine whether it is a file
os.path.isfile(<Path>)

# Determine whether it is a folder
os.path.isdir(<Path>)

# Combine folder and file name into one path
os.path.join(<Path1>[, <Path2>[, ...]])
<Ex:>os.path.join('root','test','runoob.txt')
<Output:>root/test/runoob.txt
```
