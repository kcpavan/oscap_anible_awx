List installed SCAP documents 
`rpm -ql scap-security-guide | grep -E 'ssg-.*-ds.xml'`
profiles in document 
`oscap info /usr/share/xml/scap/ssg/content/ssg-rhel7-ds.xml`