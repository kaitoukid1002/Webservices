# Webservices
Code example Webservice Upload file by Web.py

# Lib
Install lib Web from http://webpy.org/

# Hang ups
A couple of things to watch out for:
See fileupload.
Don't put the file in a folder that is executable without any check of the extension and type of file.
Actually, we need to open the fout file object in mode "wb"(in windows), ie. write binary mode, otherwise the image uploaded is broken.
