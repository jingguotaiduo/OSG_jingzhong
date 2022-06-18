Download the OSG-Install.rar and OSG-Data.rar and unzip them. Rename the OSG-Data to data.
For Windows:
1、You can edit the environment variable, by establish two new variables,like the following:
<bash>
|----name------value-----|
OSG_PATH     E:\jing_zhong\osg-install
OSG_FILE_PATH %OSG_PATH%\data;%OSG_PATH%\data\Images
 </bash>
 2、Then add the value(%OSG_PATH%\bin;) to the environment variable which named Path.
 <bash>
|----name------value-----|
Path ...;%OSG_PATH%\bin;
 </bash>
