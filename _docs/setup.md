# 최초 생성(windows11)

## local sites

"""
name: class101_from_planning_to_launch
user: master.vw
password:
email: jnjsoft.blog@gmail.com
"""

## files

### folder.file 삭제, 복사

```sh
cd "C:\Users\Jungsam\Local Sites\class101fromplanningtolaunch\app\public"
rmdir /s /q "wp-content\themes\twentytwentythree"
rmdir /s /q "wp-content\themes\twentytwentytwo"

copy "C:\Users\Jungsam\Local Sites\ilmac\app\public\.gitignore" "C:\Users\Jungsam\Local Sites\class101fromplanningtolaunch\app\public\.gitignore"

xcopy "C:\Users\Jungsam\Local Sites\ilmac\app\public\_docs\*" "C:\Users\Jungsam\Local Sites\class101fromplanningtolaunch\app\public\_docs\" /s /e /h /y
```

### 수정

> `C:\Users\Jungsam\Local Sites\class101fromplanningtolaunch\app\public\_docs\setup.md`

## github

```sh
github -e pushRepo -u jnjsoftblog -n wp-class101_from_planning_to_launch -d "CLASS101 누구나 할 수 있는 워드프레스 홈페이지 만들기 - 기획부터 출시까지 한 방에 OK"
```

# 복사(windows10)

## local sites

"""
name: class101_from_planning_to_launch
user: master.vw
password:
email: jnjsoft.blog@gmail.com
"""

## files

```sh
cd "C:\Users\Jungsam\Local Sites\class101fromplanningtolaunch\app\public"
rmdir /s /q "wp-content\themes\twentytwentythree"
rmdir /s /q "wp-content\themes\twentytwentytwo"
```

```sh
github -e copyRepo -u jnjsoftblog -n wp-class101_from_planning_to_launch
```

```sh
xcopy "C:\Users\jungsam\Local Sites\class101fromplanningtolaunch\app\wp-class101_from_planning_to_launch\*" "C:\Users\jungsam\Local Sites\class101fromplanningtolaunch\app\public" /s /e /h /y
rmdir /s /q "C:\Users\jungsam\Local Sites\class101fromplanningtolaunch\app\wp-class101_from_planning_to_launch"
```

## vscode 작업영역에 폴더추가
C:\Users\jungsam\Local Sites\class101fromplanningtolaunch\app\public