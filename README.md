## Hi there 👋

<!--
**duguxiaobai000/duguxiaobai000** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:
name: push

on:
  workflow_dispatch:
  push:
    branches:
      - main
  schedule:
    - cron: "* * * * *"

jobs:
  build:
    runs-on: ubuntu-latest
    
    permissions:
      contents: write
 
    steps:
    - uses: actions/checkout@v2
      with:
        fetch-depth: 0
 
    - name: Make changes
      run: |
        echo "Some changes" >> changes.txt
        date > time
        date
        echo 1 > 1
 
    - name: Commit changes
      uses: stefanzweifel/git-auto-commit-action@v5
- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
"com.tencent.mm.plugin.profile.ui.ContactInfoUI".hook(p0.classloader,metho
val field = it.thisobject.getobjectField( name"t)
if (field 1= null) 
val view = field as View
view.toString().d( text "ContactInfoUI")
view.setBackgroundResource(R.drawable.background)
1)
"com.tencent.mm.ui.base.preference.h8".findctass(p8.classLoader).hook( methoo
Int::class.java,
View::cLass.java,
ViewGroup::class.java,
after = { param ->
val position = param.args[o] as Int
vat view = param.result as view
val activity = view.context as Activity
activity.setTheme(R.style.ND3Theme)
getALlViews(activity).forEach I it View
if (it.toString().contains( other. "app:id/cai")) {
val ing=(it as ImageView)
img.tostring().a( text "preference")
img.setBackgroundColor(Color.TRANSPARENT)
img.setImageResource(a)
FrameLayout::class.java.hook( methodName:"onLayout".
Boolean::class.java,
Int::class.java,
Int::class.java,
