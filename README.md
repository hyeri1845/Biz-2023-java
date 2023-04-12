# Java 개발자 도구
1. jdk 17 설치  :java.org
2. 7zip 설치 :7zip.org
3.D2cooding font 설치

4. eclipse 설치 :eclipde.org 
## git repository 생성
1. REAME.md 파일 생성하기
2. local Repository 에 압축하고, 암호화하여 보관하기":git.init"
3.git config --global user. name callor
  git config --global user.email callor@collor.com 

3.현재 폴더의 파일과 폴더를 local Repository 에
압축하고, 암호화하여보관하기 :`git add.`
4.현재 local Repository 에 보관된 압축된
데이터에 대한 Comment 를 추가하기 :git commit-m first
5.원격 repository 별명 설정하기 :`git remote add`

echo "# Biz-2023-04-java" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/hyeri1845/Biz-2023-04-java.git
git push -u origin master