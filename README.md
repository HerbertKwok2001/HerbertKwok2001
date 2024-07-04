- 👋 Hi, I’m @HerbertKwok2001
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
HerbertKwok2001/HerbertKwok2001 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
Threat Intelligence
Incident handling with Splunk 

1.	Information Gathering
1.1	Threat Intelligence Mailbox
-	Use a category to inspect the necessary log
Condition(tbd): Nature/Score/Call for action (will be elaborated in detail section by section)


2.	Analysis
2.1	Matching
-	Whether IP match the IOC/Previous IP in splunk
2.2	Evaulation
-	Investigation (VT, abuseipdb)
-	FP (Examples of stakeholders, procedures after confirming FP)

3.	Disseminate analysis
3.1	Create Jira Ticket
-	(Similar to SOC playbook)
3.2	Escalate to Stakeholder (will list out what condition need to be fulfilled)
-	(Similar to SOC playbook) (e.g., Splunk, Network Team, localstorage for record)
3.3	Incident Response (will list out what condition need to be fulfilled)
-	HKMA (Andy, Alex)
-	PwC (Michael Ching)

In inventory list provided by OGCIO and investigated by our SOC:

HKMA related which cause potential impact(call for action) eg Cisco, paloalto etc

Cybersecurity related: splunk, java,python etc
----------------------------------------------------------------------------

Virustotal:
- Enhancement: VirusTotal Enterprise

Source: OSINT
Confidence: High
TLP: AMBER
Target Sector: Supply Chain
Target Country: Worldwide
Identified TA: China-based CDN company "Funnull"
TA Type: Information technology

TTP:
T1059 - Command and Scripting Interpreter

IOC:
https://kuurza.com/redirect?from=bitget
https://www.googie-anaiytics.com/html/checkcachehw.js
https://www.googie-anaiytics.com/ga.js
4.bootcss.com
ad15.bootcdn.net
alpinejs.bootcss.com
api.staticfile.org
assemblyscript.bootcss.com
assets.bootcss.com
babel.bootcss.com
blitzjs.bootcss.com
bluebird.bootcss.com
bootcdn.net
bootcss.com
bot.unionadjs.com
browsersync.bootcss.com
bulma.bootcss.com
cd.polyfill.io
cdan.bootcdn.net
cdn.bootcss.com
cdn.polyfill.io
cdn.staticfile.org
cdnjs.bootcdn.net
cdnjs.bootcss.com
chartjs.bootcss.com
cheeriojs.bootcss.com
clipboardjs.bootcss.com
code.bootcdn.net
codeguide.bootcss.com
create-react-app.bootcss.com
d.bootcss.com
deno.bootcss.com
docker.bootcss.com
docs.bootcss.com
docusaurus.bootcss.com
ejs.bootcss.com
esbuild.bootcss.com
eslint.bootcss.com
expo.bootcss.com
fastify.bootcss.com
formik.bootcss.com
gitdocs.bootcss.com
global.bootcdn.net
graphql.bootcss.com
handlebars.bootcss.com
hexo.bootcss.com
icon.bootcss.com
icons.bootcss.com
image.bootcss.com
infima.bootcss.com
jekyll.bootcss.com
jestjs.bootcss.com
job.bootcss.com
jquery.bootcss.com
jsdoc.bootcss.com
koa.bootcss.com
koajs.bootcss.com
legacy.polyfill.io
lernajs.bootcss.com
less.bootcss.com
liquid.bootcss.com
markdown.bootcss.com
mb.bootcss.com
mocha.bootcss.com
mochajs.bootcss.com
moment.bootcss.com
momentjs.bootcss.com
nestjs.bootcss.com
nextjs.bootcss.com
nginx.bootcss.com
nodejs.bootcss.com
nunjucks.bootcss.com
open.bootcss.com
parceljs.bootcss.com
playwright.bootcss.com
polyfill.io
polyfillcache.com
polyfillcdn.com
polyfilldns.com
popperjs.bootcss.com
preact.bootcss.com
prettier.bootcss.com
prisma.bootcss.com
progit.bootcss.com
pug.bootcss.com
pugjs.bootcss.com
puppeteer.bootcss.com
purecss.bootcss.com
qa.polyfill.io
qiniu.staticfile.org
react.bootcss.com
reactjs.bootcss.com
reactjsbeta.bootcss.com
recoiljs.bootcss.com
reduxjs.bootcss.com
rematchjs.bootcss.com
remotion.bootcss.com
rollup.bootcss.com
romejs.bootcss.com
rust.bootcss.com
sass.bootcss.com
semver.bootcss.com
serverjs.bootcss.com
socketio.bootcss.com
ssl.bootcss.com
staff.bootcss.com
static.bootcss.com
staticfile.org
stylelint.bootcss.com
stylus.bootcss.com
sweetalert.bootcss.com
swift.bootcss.com
swr.bootcss.com
tippy.bootcss.com
tippyjs.bootcss.com
tsdoc.bootcss.com
typeorm.bootcss.com
typescript.bootcss.com
underscorejs.bootcss.com
unionadjs.com
v2.bootcss.com
v3.bootcss.com
v4.bootcss.com
v4ing.bootcss.com
v5.bootcss.com
vitejs.bootcss.com
vue.bootcss.com
vuejs.bootcss.com
vuepress.bootcss.com
w3schools.bootcss.com
wasm.bootcss.com
wasm.polyfill.io
webpack.bootcss.com
wenda.bootcss.com
www.bootcss.com
yarn.bootcss.com
yarn2.bootcss.com
youzhan.bootcss.com
zeptojs.bootcss.com
staticfile.net
xhsbpza.com
union.macoms.la
newcrbpc.com

Ref: https://sansec.io/research/polyfill-supply-chain-attack
https://www.virustotal.com/gui/collection/2dc00dfc86cd08368bf364e074f23912c29642d7178fcf1d86f388da2666565d/iocs

