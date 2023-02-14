
# Linux Command Line Practical

### 1. write a command to create new folder

`
    mkdir test_folder
`

### 2. write a command to find the current path of the folder
`
    pwd
`

![image](https://user-images.githubusercontent.com/122258263/218739719-d83ad350-73dc-4e43-88a3-c1d8ad8e992a.png)

### 3. write a command to move into new created folder
`
    mv test_folder test_folder2
`
![image](https://user-images.githubusercontent.com/122258263/218740151-2426fdc4-84a7-41b9-8867-99e685c1b1fe.png)


### 4. write a command to create new file
`
    touch new.txt
`


### 5. write a command to add some content in a file
`
    gedit new.txt
`

![image](https://user-images.githubusercontent.com/122258263/218741504-4fac2d3a-0d6e-46e1-9bbd-b75056349ee5.png)


### 6. write a command to find a specific word from a file
`
grep "the" new.txt
` 

![image](https://user-images.githubusercontent.com/122258263/218742215-d0901e3a-ba81-4a42-bd7f-41380d3befd7.png)


### 7. write a command to find the size of a file
`
ls -l new.txt
`

![image](https://user-images.githubusercontent.com/122258263/218743672-6c0a99df-bda6-47b2-91ba-98997664645d.png)

 
### 8. write a command to rename that file

`
mv new.txt new_update.txt
`

![image](https://user-images.githubusercontent.com/122258263/218744448-1489f751-803d-43b2-b878-5ed3b7e4faeb.png)


### 9. write a command to make a copy of a file with another name

`
 cp new_update.txt new_update2.txt
` 

![image](https://user-images.githubusercontent.com/122258263/218744877-ecec6d37-b53b-46a3-abea-e8e30be085b7.png)


### 10. write a command to show the list of files in folder

`ll`

![image](https://user-images.githubusercontent.com/122258263/218745099-ce97f6df-1425-4935-a177-aacefeba79c9.png)


### 11. write a command to move that file to desktop

`
sudo mv new_update2.txt /Desktop
`

![image](https://user-images.githubusercontent.com/122258263/218745634-8db9cc61-96ef-42ab-940f-4ab4305a64fd.png)


### 12. write a command to change permissions of the file

`sudo chmod 567 new.update.txt`


![image](https://user-images.githubusercontent.com/122258263/218746823-727c1d4a-e2e9-4012-ae83-7dbd45643eec.png)


### 13. write a command to delete file


`
rm new_update.txt
`

![image](https://user-images.githubusercontent.com/122258263/218747051-4040d382-f0d7-4f90-b92a-4965bf3ad8b0.png)



### 14. write a command to delete created folder

` 
rm -r test_folder2
`

![image](https://user-images.githubusercontent.com/122258263/218747621-1042fe4d-fa73-4e3d-959a-b9fc324966e2.png)


### 15. write a command to command to find a any file on local machine

`
    find . -type f -name "*.txt"
`

![image](https://user-images.githubusercontent.com/122258263/218748675-6a8e9a44-42c1-4264-a53a-17fca91ffffd.png)


### 16. write a command to create a zip of files from specific path on local machine


`
zip -r temp.zip test_folder/
`

![image](https://user-images.githubusercontent.com/122258263/218750118-aa97bf3b-dff5-47f2-8829-7c46073d6bff.png)

### 17 write a command to unzip

`
unzip temp.zip
`

![image](https://user-images.githubusercontent.com/122258263/218750583-801e2b15-2b91-4a8d-b511-8bc2f29bbb17.png)


### 18. write a command to download file from specific location on the internet

`
wget link_to_file
`


### 19. Write command to see last 10 lines of a file.

`
tail new.txt
`

### 20. Write command to see history of a file.

## Authors

- [@aayush-vyas](https://www.github.com/aayush-vyas)

