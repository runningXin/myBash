# utilities

Repository of my own favirite utilities tools. 



sudo du -ab / —max-depth=3 —exclude=‘/data’ | sort -n -r | head -n 100 | awk '{numfmt --to iec $1 }'| awk '{print $1 "\t" $2 }'

du -ab --max-depth=3 --exclude='/data' / | grep -v "Permission denied" | sort -n -r | head -n 200 |    numfmt --to iec

du -ab --max-depth=3 --exclude='/data' / | grep -v "du: cannot read directory" | sort -n -r | head -n 200 |    numfmt --to iec


find     .    -type f -newermt 2019-05-29 ! -newermt 2019-05-30 -exec mv {} /tmp \;

event title— response kit uses lstm to identify a message is an event by analyzing per-word polarities (proposal, confirmation, rejection, neutral)

GitLab Repo
Set up SSH
ssh-keygen
cd .ssh/
cat id_rsa.pub and paste to gitlab web site
git clone git@gitlab.sd.apple.com:danielgross/templatebuilder-data.git
source source-me
python -m webui.server
brew install python
pip install pylint —upgrade
git branch
git log
git history -5
git checkout whitetail
git pull origin whitetail
git pull origin
git apply filename.patch (apply patch file)
git checkout -b branchname
git push —set-upstream origin mybranchname
grep -l -Z -r aaa *.xml | xargs -I {} mv {} xin/
git commit —no-verify
git rm —cached filename

git remote -v

git add debtor/*

RegEx
(\d{3,4}[.-]?)+
\[(.+)\].*机票订单(.+?),(.+?),(\d{1,2}月\d{1,2}日)(\d{1,2}:\d{2})(.*航空)([0-9a-zA-Z]+)(.+)机场(.+)航站楼-(\d{1,2}:\d{2})(.+)机场
\[(.+)\].*机票订单(.+?),(.+?),(\d{1,2}月\d{1,2}日)(\d{1,2}:\d{2})([\u4e00-\u9fa5]*)([0-9a-zA-Z]+)(.*)(机场)?(.*)(航站楼)?-?(\d{1,2}:\d{2})?(.+)机场?
\[*(.+?)\]*确认:订单(\d+)(.+)(\d{1,2}月\d{1,2}日)至*(\d{1,2}日*)*(.+?店).*地址:(.+?)([0-9\-]+);
.*确认:订单(\d+)(.+)(\d{1,2}月\d{1,2}日)至*(\d{1,2}日*)*(.+?店).*总价(.+);.*地址:(.+?)([0-9\-]+);
.*机票订单(.+?),(.+?),(\d{1,2}月\d{1,2}日)(\d{1,2}:\d{2})([\u4e00-\u9fa5]*)([0-9a-zA-Z]+)(.*机场).*-(\d{1,2}:\d{2})?(.+机场)
.*机票订单(.+?),(.+?),(\d{1,2}月\d{1,2}日)(\d{1,2}:\d{2})([\u4e00-\u9fa5]*)([0-9a-zA-Z]+).+?([\u4e00-\u9fa5]*)-(\d{1,2}:\d{2})?(.+机场)?
订单(.+)，『(.+?)\s(.+?)\s(.+?)-(.+?)\s(\d{1,2}月\d{1,2}日\d{1,2}:\d{1,2}-\d{1,2}月\d{1,2}日\d{1,2}:\d{1,2})\s(.+)』建议您提前120分钟至机场办理值机。
RegEx website
https://regex101.com
http://regexr.comschema.orghttps://mailbox-js.apple.com/dashboard/grading
/*jshint esversion: 6 */
install pylint
git log
1596 git remote -l
1597 git remote -v
1598 git push origin master
1599 git pull origin master
1600 git push origin master

control rasperri pie with siri
