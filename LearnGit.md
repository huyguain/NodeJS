# Learn Git
## 1. Giới thiệu 
## 2. Why use?
## 3. Install 
- Ubuntu
    ``` javascript
    $ sudo apt-get install git
    ```

- Thiết lập chứng thực cá nhân:
	``` javascript
	$ git config --global user.name "Thach Pham"
	$ git config --global user.email "contact@thachpham.com"
	```
## 4. TẠO MỘT REPOSITORY
- Tạo local
	``` javascript
	$ git init git_example
	```

- tracked:
	``` javascript
	$ git add readme.txt
	$ git status
	```
- Commit:
	``` javascript
	git commit -m "First Commit"
	```
- Clone:
	``` javascript
	$ git clone https://github.com/thachphamblog/hoc-git
	```
- dùng lệnh git push để đẩy các tập tin đã được commit lên Github
	``` javascript
	$ git push origin master
	```
## 5. COMMIT VA STAGING AREA
- Staging area
	git add để đưa 