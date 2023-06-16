# Jean-Zay administrative procedures

## Jean-Zay access procedure

Our experience is that the access procedure for Jean Zay takes roughly 3 weeks
(add 1-2 months on top of that if you have to go through additional security
background checks). It does seem long but it is definitely worth it.

!!! tip
    Find people that have accessed IDRIS or GENCI clusters around you. If you
    have no idea who they may be, your local IT may know, ask them. They may
    save you a lot of time, because they have gone through a similar procedure.

### Overview of the procedure

Here we will focus on the easiest procedure to access Jean Zay, namely the
"Accès dynamique" one. This procedure only applies if your research is around
developing AI algorithms. Here is a quick overview of the procedure. Each step
is detailed in the sections below.

1. Create an [EDARI account](https://www.edari.fr/splogin) (simple
   personal details). See [this](#edari-account-administrative-account)
   for all the details about this step.
2. Fill a form about your project (**"Déclaration de dossier"**). Hardest part
   is to figure out who your "Directeur de la structure de recherche" is and to
   have the form signed by him/her. You also need to write a few lines about
   your project. See [this](#d%C3%A9claration-de-dossier-project-description)
   for all the details about this step.
3. Fill a form about to get a computing account (**"Déclaration de compte
   calcul"**). Hardest part is to figure out who your "Responsable Sécurité
   informatique" is and have the form signed by him/her as well as the
   "Directeur de la structure de recherche". You also need to declare one (or
   more) IP address(es) that will be able to use to connect to Jean Zay. See
   [this](#declaration-de-compte-calcul-computing-account-creation-for-jean-zay)
   for all the details about this step.
4. Additional security background checks in some cases. Unfortunately
   this takes 1-2 additional months. See
   [this](#additional-security-background-checks-in-some-cases) for all the
   details about this step.
5. After roughly a week, you'll get an email from IDRIS giving you your login,
   password and instructions to connect to Jean Zay. See
   [this](#idris-email-with-login-and-password) for all the details about this
   step.
6. After roughly 2 days, you should be able to connect to Jean Zay.

### Institute-specific information

Some institute-specific things are best put on a non-public repo, e.g. email
addresses of persons to contact. Here are links to some Institute specific
information:

- Inria: https://gitlab.inria.fr/jean-zay-users/inria-specific-jean-zay-doc

Feel-free to do a PR to add your own institute link! This is probably best if
this kind of repo is behind Institute-specific authentication.

### EDARI account (administrative account)

!!! info "Estimate of the time needed:"
    5 minutes.

To create an EDARI account, it is recommended to use
https://www.edari.fr/splogin which It is available for a wide range of academic
institutions through RENATER. It will ask you your institute credentials and may
make your life easier by automatically filling some info for you (e.g. your
institude security person and your head of the lab)

Alternatively use https://www.edari.fr/user/register (for example if you can not
find your institution in the first link)

!!! note
    If you have clicked on a red button like the one below at one point, it is the
    same thing as using the recomended link and some info may be automatically
    filled for you.

    <img src="../img/edari-federation-renater.png" width="50%" style="margin-top: 0.2em" style="display: block"/>


!!! tip
    In case something goes wrong:

    - Contact for [EDARI account](https://www.edari.fr/contact)
    - [EDARI FAQ](https://www.edari.fr/faq)

### "Déclaration de dossier" (project description)

!!! info "Estimate of the time needed:"
    15 minutes (fill the form) + 1-2 days (figure out the right person to sign
    the form and get him/her to sign it).

On your [EDARI user space](https://www.edari.fr/utilisateur), click on the
"Intelligence Artificielle" section and then "Déclaration de dossier" and then
"Constituer un dossier".

!!! note "Important details:"
    - "Directeur de la structure de recherche" : head of the lab, head of the
      department, head of the institute, do what is easier for you.
    - As long as you ask for <= 10000 GPU hours (~400 days on a single GPU) and
      less than 48 GPUs simultaneously (4 GPUs on 12 nodes) it should go through
      easily.
    - Project description : no need to spend too much time on this, 3-5 lines
      should be plenty enough if you ask for less than 10000 GPU hours.

When you finish filling out this part, you should something like this:
<img src="../img/project-saved.png" width="80%" style="display: block"/>

!!! warning "Important"
    You need to click on "Valider la saisie des informations" to validate your
    information:
    <img src="../img/project-validate.png" width="80%" style="display: block"/>

Note that in principle once your 10000 GPU hours are exhausted you can ask for
a renewal through a similar "lightweight" procedure, see [this](#how-to-renew-hours) for more
details.

### "Déclaration de compte calcul" (computing account creation for Jean Zay)

!!! info "Estimate of the time needed:"
    15 minutes (fill the form) + 1-2 days (figure out the right person to sign
    the form and get him/her to sign it).

!!! note "Important details:"
    - "Responsable sécurité informatique", this is someone that should be able
      to turn deny you access to Jean Zay, in case there is any issue with your
      account activity. He/She must be able to certify that you respect the IT
      charter in your host lab/institution. In CNRS labs, he/she is known as
      the CSSI (Chargé·e de la Sécurité des Systèmes Informatiques).
    - IP addresses to connect to Jean Zay. Make sure they are static IP
      addresses (e.g. not your IP address from you home). In most cases: your
      desktop in your lab will have a static IP address, but best confirm with
      your local IT people. Note that the form is helping you with some
      suggestion which were correct when filling it from a fixed desktop in our
      lab.

When you finish filling out this part, you should see something like this:
<img src="../img/computing-account-saved.png" width="80%" style="display: block"/>

!!! warning "Important"
    You need to click on "Valider la saisie des informations" to
    validate your information:
    <img src="../img/computing-account-validate.png" width="80%" style="display: block"/>


### Additional security background checks in some cases

In some cases, the direction of IDRIS can require additional security
background checks.

You will have to fill a form with basic information about
yourself (name, address, date and place of birth) and about the project you
will be working on: where you will be working from, where your financing comes
from (e.g. Inria, a project grant, etc ...), and a description of your project.

The project description comes in two parts:

- A short description (can be the same as the one used in your declaration on
  Edari) embedded in the form you will receive.
- A more detailed description to attach in PDF. A one-page file with half
  description / half bibliography should be enough. You will also be asked to
  attach a CV. It must include everything you did after you obtained your last
  degree. Every blank should be explicitly stated. For example, if you had a
  one month break, you should specify this month on your CV and state « No
  employment » next to it.

After all the paperwork has been submitted, you should receive an e-mail saying
that the security background chekcs will take between 1 and 2 months. The 2
months is a hard limit and is actually warranted by law. Do not hesitate to
send them an email asking about the status of your application if you don't
hear from them maybe after 1 month the first time, and then every two weeks
until you manage to get through the security background checks (fix this part
if you have better recommendations).

Once this step is complete, the regular procedure applies.

### IDRIS email with login and password

In principle, you should receive a "Ouverture de votre compte" email from IDRIS
roughly one week after having completed the previous step. Contact:
[assist@idris.fr](mailto:assist@idris.fr) if you have not received email within
a week.

- Quite a long email with detailed instructions. One the first connection your
  password is the concatenation of the first password in "Déclaration de compte
  calcul" and the password in the email. You are then asked to chose a new
  password.
- Count 2-3 days after the email to actually be able to access Jean Zay. Some
  time is needed for the IP address to be added to Jean Zay.


### How to add additionnal IP addresses to your authorised IP addresses

!!! info "Estimate of the time needed:"
    15 minutes (fill the form) + 1-2 days (figure out the right person to sign
    the form and get him/her to sign it). + 1-2 days (until the change actually
    takes effect on the IDRIS side).

To add additionnal IP addresses to those mentioned on your original declaration:

- Fill the "Ajout, modification ou suppression de machines" table on page 2 of
  [this pdf
  document](http://www.idris.fr/media/data/formulaires/fgc.pdf#page=2).
- Have it signed by your "Responsable sécurité informatique".
- e-mail the signed form to gestutil@idris.fr and wait 1-2 days until the change
  actually takes effect.

## How to write a project proposal (only needed if you request more than 10k GPU hours)

!!! info "Estimate of the time needed:"
    1h (write a project) + a few days/weeks for approval (depending on the
    request).

Useful when you have used most of your computing time and want to fill a
"Demande de ressources au fil de l'eau" (request more hours on the fly), and
you would like to ask for more than 10k GPU hours.

- Describe the scientific project for which you need to perform experiments. Be
  specific about the team you work in, why do you need such computing
  ressources
- Estimate the number of hours you will need. To provide an estimate you can
  estimate your daily/weekly computing time `C` you need and multiply by the
  number of months `M` you want to work on Jean-Zay for this project to get
  `T = C * M`.
- Describe a typical experiment. How much computing ressources do you need: do
  you use 1 GPU per experiment or 10 GPUs, if 10 why, can be useful to justify
  your daily need of computation `C`. Be specific about the algorithms you are
  using, the data type (image, text, audio, video ...), the model you use (cnn,
  lstm, kernels, ...) and what your model is used for (predicting image labels,
  pose estimation, robot movements, ...)
- Include references to back up your project. If you already have published, it
  is definitely a plus.

Depending on your request, this proposal can be reviewed by 1 to 10 people.

## How to renew hours

!!! info "Estimate of the time needed:"
    30 minutes (fill the form and write an activity report) + 1-2 days (figure
    out the right person to sign the form and get him/her to sign it).

Hours are allocated for one year so you need to renew them after one year. You
will get a reminder email roughly one month in advance. The same procedure
applies if you have used almost all your hours and you want to ask for more.

The procedure is fully detailed
[here](http://www.idris.fr/eng/info/gestion/demande-heures/documentation-ad/renouvellement-dossier-ad-eng.html)
but here is a short summary to know what to expect:

- the procedure happens on https://www.edari.fr/utilisateur. The main thing is
  to ask for the number hours you want (GPU and potentially CPU).
- you need to write an activity report (PDF), about half a page should be
  enough. The main idea is to show that you made good use of the hours, for
  example by listing publications. There is an activity report template
  [here](http://www.idris.fr/media/ia/ressources/modele-rapport-ad.pdf) (in
  French) that may help you. Also remember to acknowledge Jean-Zay in your
  article (see [this](#how-to-cite-jean-zay-in-your-article) for more details).
- download a PDF summarizing your renewal application, get it signed by your
  "directeur de recherche" and upload it on the EDARI website. In some cases
  this step happens automatically (the "directeur de recherche" gets an
  automated email and can validate your project directly)

## How to cite Jean-Zay in your article

This is important if you want Jean-Zay to get the credit it deserves and may
help to get more funding and eventually to get more compute nodes.

Add this to your acknowledgments:

> This work was performed using HPC resources from GENCI–IDRIS (Grant [year]-[project number])

for example (if you project was allocated hours in 2021 and your project number
is AD12345678):

> This work was performed using HPC resources from GENCI–IDRIS (Grant 2021-AD12345678)

You can find your project number in eDARI: https://www.edari.fr/utilisateur
When connected via `ssh` to the Jean-Zay cluster, you can also know your project number (as well as your remaining budget) using the command line `idracct`.

The official guidelines for Jean-Zay citation are available here:
http://www.idris.fr/eng/info/gestion/remerciements-eng.html
