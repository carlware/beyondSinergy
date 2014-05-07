## Add beyond compare to Rational Sinergy 7.1

1. Copy bc3_compare.bat and bc3_merge.bat to beyond compare folder
2. In "C:\Program Files\IBM\Rational\Synergy\7.1\etc\ccm.properties" update
	1. ```windows.tool.merge.ascii = "c:\program files\beyond compare 3\bc3_merge.bat" "%file1" "%file2" "%ancestor" "%outfile" "%file1_label" "%file2_label" "%ancestor_label"```
	2. ```windows.tool.compare.ascii = "c:\program files\beyond compare 3\bc3_comp.bat" "%file1" "%file2" "%file1_label" "%file2_label"```

## TODO
	1. Automate installation with python