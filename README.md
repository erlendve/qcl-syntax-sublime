qcl-syntax-sublime
==================

A syntax definition for QCL (Qualiware Command Language) to be used with [Sublime Text](http://www.sublimetext.com/)

Install by copying the files into the "folder for userdata"\AppData\Roaming\Sublime Text 3\Packages\User

Current features:
- Highlights specific qcl symbols like: -> and -<
- Special feature: text inside single quotes are highlighted as html.
  - This means: Use " for normal strings, and ' when writing html
- Generate StrAppend snippet by writing "stra" and pressing tab (to autocomplete)
- Supports highlighting of a lot of common QCL specific functions like: obj->Contains, obj->FramedBy etc.

Screenshot:  
![Screenshot of qcl with some html in Sublime Text](sublimescreenshot.png)
