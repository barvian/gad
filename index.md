---
layout: essay
date: 2015-05-14
author:
  name: Maxwell Barvian
  url: http://barvian.me
---

# A self-help iPhone app for GAD (Generalized Anxiety Disorder)

{% include meta.html %}

{% include youtube.html src="https://www.youtube.com/embed/PTSoapSWG4M" %}

Generalized Anxiety Disorder (GAD) affects about 3.1% of American adults (aged 18 years or older) in a given year, totaling about 6.8 million people {% include c.html r=3 %}.  The average age of onset is 31 years old, though it often develops gradually between childhood and middle age.  Treatment for GAD has been the subject of extensive academic research, and many techniques have proven effective in dealing with both short and long-term symptoms.

The iOS platform is one of the most popular available, and its mobile application market already features tools to help patients with anxiety, diabetes, cancer, and other illnesses.  Combined with its thriving and powerful development toolkit, iOS offers an extremely promising opportunity for GAD patients to treat their symptoms privately through interactive self-help techniques.

The goal of this exercise was to prototype an interactive self-help iPhone application that offers a comprehensive recovery program for all GAD patients by incorporating principles from some of the most heavily researched treatments available.

<TOC />

## Background

### Generalized Anxiety Disorder (GAD)

Anxiety in itself is not a disorder.  As anxiety specialist Dr. Edmund Bourne {% include c.html r=0 a=false %} and other experts have noted, anxiety is often considered inevitable in contemporary society. Worrying can be a useful, appropriate response to challenging situations in everyday life.  It becomes a diagnosable disorder, however, when a person worries excessively about a variety of everyday problems for at least 6 months {% include c.html r=3 %} in a way that noticeably interferes with their normal lives. Physical symptoms of GAD can include fatigue, headaches, nausea, twitching, muscle aches, and irritability; mentally, patients can’t relax, startle easily, and have difficulty falling asleep.

#### Treatment

Relapse is a major concern for GAD patients. Treatment options that address one or two contributing causes -- biology, upbringing, conditioning, stressors, self-talk and belief, ability to express feelings, etc. -- usually only alleviate GAD symptoms temporarily.  According to Bourne {% include c.html r=0 a=false %}, a complete program of recovery from an anxiety disorder must reduce physiological reactivity, eliminate avoidance behavior, and change subjective interpretations or self-talk which perpetuate a state of apprehension and worry. Meta-analyses have already shown computer-based self-help treatments to be effective in these areas {% include c.html r=2 %}.

#### Cognitive-Behavioral Therapy (CBT)

GAD patients tend to view the world as a threatening place, a misperception that can intensify quickly and lead to a downward spiral of anxious responses {% include c.html r=5 %}.  Cognitive-behavioral therapy (CBT), one of the most popular treatment options available for GAD, is based on this observation.  Self-monitoring is foundational to CBT; patients are taught to pay attention to their anxiety level throughout daily activities to catch patterns of worrisome thinking early on and cope with them immediately using a variety of techniques.  These can be personalized from patient to patient, but often include practices like meditation, guided imagery, muscle relaxation, deep breathing, etc.

#### Positive Psychology

Positive psychology is a semi-structured treatment for depression and anxiety that tries to shift patients' focus towards positive emotions and personal strengths.  Techniques can include daily exercises that emphasize positive experiences or structured journals to record such episodes of wellbeing.  Positive psychology was designed as a complement to more comprehensive methods like CBT, not a freestanding alternative in its own right.  That being said, studies show that positive psychology (also called Well-Being Therapy) paired with CBT can be more effective at preventing relapse in GAD patients than CBT alone {% include c.html r=1 %}.

### iOS Design

Whenever applicable, the design of this application defers to well-researched principles and documented guidelines rather than personal preference in an attempt to diminish or at least remain neutral to symptoms of GAD, never contributing to them.  Great care will be taken to ensure its design is easy to follow, unobtrusive, and consistent with other platform applications.

#### Color Psychology

Broadly speaking, color psychology is the study of color as it affects mood, emotions, and behavior.  Though research in this area is sometimes criticized for its inconsistency, some studies make undisputed implications for software design. The reason red is almost always used in error messages or alert dialogs, for example, is because the color has been found to excite more emotion than neutral colors like blue and green {% include c.html r=4 %}. An orange headline may draw more attention than a gray one, for example, while a light blue background may feel more calming than a white one.  Colors in this application were chosen based on relevant research in an attempt to ease users rather than exacerbate their anxious symptoms.

{% comment %}
### Related Applications

There are several iOS applications that already address anxiety or at least offer some of the same treatment strategies as this application.  A quick search of the App Store for “anxiety” returns 852 results; a small, diverse sample of these will be discussed briefly below along with their respective strengths and weaknesses.

#### Self-help for Anxiety Management (SAM)

[SAM](https://appsto.re/us/ljHVN.i) from the University of the West of England offers much of the same functionality as this application.  Its default screen, shown below in {% include fr.html f="sam_home" %}, highlights this fact: among the options listed are techniques for relieving anxiety symptoms immediately, a self-monitoring tool that allows users to log their level of anxiety at any time (with an accompanying tracker that shows a graph of these logs), and a “social cloud” that allows users to post comments about their anxiety and reply to other users’ concerns.

{% include f.html f="sam_home" align="left" %}

SAM clearly hopes to offer a comprehensive treatment program for anxiety patients. The relaxation techniques are robust and easy to follow, and all of the application’s features work as advertised.  The app has also received numerous positive reviews on the App Store, which is excellent. That being said, one improvement that may help the application better service its users is an improved flow. The grid of options seen in {% include fr.html f="sam_home" %}, for example, is certainly useful, but doesn’t seem to guide users through the anxiety recovery process. Of course, users can tap the first button, “Working with SAM”, to get more information, but it’d be more helpful to incorporate the recovery process into the interface design itself without hiding it behind a button.  The grid also makes all the options look equally as important, even though some, like “Help for Anxiety NOW”, may be far more relevant if the user is currently experiencing an anxious episode (which would be a reasonable explanation for launching SAM in the first place).  Overall, though, SAM likely gets more right than wrong, and it’s encouraging to see another anxiety application having a positive impact on users' lives.

#### Calm

This [free application](https://appsto.re/us/QZpfI.i) by Calm.com, Inc. focuses exclusively on meditation and relaxation techniques. According to the application description, it includes: 7 guided meditation sessions, 10 “immersive nature scenes”, 16 relaxing music tracks, and 50 additional, purchasable guided meditations.  Its user interface, shown in {% include fr.html f="calm_home" %}, revolves around a user-customizable looping scene, which defaults to a video of rain on leaves.

{% include f.html f="calm_home" align="right" %}

Like SAM, however, Calm’s main screen might benefit from an improved visual hierarchy.  The “Programs” button, which launches a full list of available meditation programs, certainly seems to be the most important tool available on this screen, though it’s given equal visual importance as the “Scenes” button which simply changes the background of the application. Calm’s meditation programs, on the other hand, are well-structured and provide clear starting points for relieving anxiety-related symptoms; the “7 Days of Calm” program shown in {% include fr.html f="calm_program" %} is exemplary.

{% include f.html f="calm_program" align="left" %}

Unfortunately, Calm also lacks any positive psychology/relapse prevention tools, though it doesn’t claim to target GAD patients in particular, so this choice may have been intentional.  In any case, the application’s limited scope and focused design are commendable and fully deserving of the many positive reviews from the App Store.

#### Takeaways

This application will attempt to preserve some of the core functionalities, reading materials, and relaxation techniques found in SAM with a more guided approach like Calm's, in addition to its own Positive Psychology exercises for long-term relapse prevention.
{% endcomment %}

## Process

### Ideation

In brainstorming this application it was important to create a list of essential functions users would need from a guided anxiety recovery process.  Based primarily on the background research from the previous section, three core features were decided upon:

{:.numbered-list}
1. ##### GAD Reading materials
  For analytical personalities it can be helpful to read objective, scientific explanations of anxiety and its symptoms; they offer a chance to step back from the unpleasant feelings associated with the disorder and gain a clearer understanding of their origin. Moreover, any application that would attempt to guide users through an anxiety recovery process would warrant at least a vague description of the actual disorder itself. This should instill a sense of confidence in the user about the application's approach to recovery, and make them more likely to continue using it.
1. ##### Immediate symptom relief
   A key component in anxiety recovery is the alleviation of anxious symptoms, including shortness of breath, intense agitation and confusion, and the others mentioned in the background section. Studies on CBT offer a wealth of relaxation techniques, so the only work needed here was to decide which ones could most benefit from an interactive user experience, then realistically determine how many could be developed within the project's timeframe. The following exercises were eventually selected:
     1. Deep breathing
     1. Calming scene (i.e. a video/image of a peaceful landscape)
     1. Guided meditation
     1. Coping statements

   These will be covered in greater depth in a later section.
1. ##### Long-term shift towards positivity
   Equally important to this application as the previous CBT-related features is a Positive Psychology aspect to prevent relapses during the recovery process.  Much of the literature seems to agree that the most helpful technique for creating such a shift is to keep a daily journal of positive events, no matter how trivial.  It was decided that such a journal would be integrated into this application.

This short list made it easier to focus on only the most important aspects of the application at all times in the design process.

### Design

#### Goals

Before layout, color palettes, interactions, or any specific detail of the application's visual design were considered, a few goals were solidified to keep in mind over the duration of the design process.

{:.numbered-list}
1. ##### Ease of use
   This goal is trivial but helpful to keep in mind considering the target audience for the application.  The design of this application should never be obtuse, or present an unnecessary burden to the user's experience.  If the user is already in an unpleasant or agitated mental state -- a likely possibility given the nature of the disorder -- this application should not exacerbate it.
1. ##### Essential aspects of anxiety recovery
   Though the feature set of this application was kept to a bare minimum, users needed to be provided as complete a self-help anxiety recovery program as possible.  Ideally, the application could confidently stand on its own as a starting point for relapse-free anxiety treatment, and easily allow for the possibility of extending it through more specific applications, such as [Headspace](https://www.headspace.com) or [Calm](http://calm.com) for a more comprehensive meditation practice.
1. ##### Unobtrusive yet involved 
   This was the most important balancing act in designing the application. Consistency is important when attempting to overcome anxious symptoms; it's easy to "forget" to practice relaxation techniques when everything feels like it's going smoothly, though repetition is a key aspect of long-term anxiety recovery.  On the other hand, users shouldn't start perceiving the application as an annoyance more than an aid, so being mindful of this distinction as much as possible seemed paramount.

#### User Personas

As an additional aid in the design process, four personas were created as representations of the application's target audience, guided by research of GAD symptoms and recurring personality traits.  Anxiety often develops gradually between childhood and middle age {% include c.html r=3 %}, so three of the four example users are in their early 20s or 30s. Female GAD patients outnumber males, but for simplicity’s sake both genders are equally represented.  The other characteristics -- hobbies, life situations, ethnicity -- are either arbitrary or specified for diversity purposes:

<ul class="block-list">
	{% for persona in site.data.personas %}
		<li>{% include p.html p=forloop.index %}</li>
	{% endfor %}
</ul>

This step helped establish a clear direction for the application's design. By putting a face (albeit imaginary) to these users, it became easier to establish a visual hierarchy for the application, prioritize certain features over others, and limit the number of overall screens to a bare minimum. These personas were referred to repeatedly throughout the rest of the design process.

#### Wireframes

With personas, goals, and core features in place, I sketched wireframes with some initial ideas for the application's layout and main screens:

{% include f.html f="learn_wireframe" %}
{% include f.html f="relax_wireframe" %}
{% include f.html f="reflect_wireframe" %}

These wireframes served well for the remainder of the design stage. The choices and thinking visible here will be explained in detail below.

#### Final mockups

I used ([Sketch](http://bohemiancoding.com/sketch/)) to flesh out the wireframes into workable high-fidelity mockups:

<div class="wrapper__wider">
	<ol class="grid grid--2 grid--3@full">
		<li>{% include f.html f="learn" %}</li>
    <li>{% include f.html f="relax" %}</li>
		<li>{% include f.html f="reflect" %}</li>
	</ol>
</div>

The application is divided into three primary actions: "Learn", "Relax", and "Reflect", each representing one of the core features described above.  A tab layout was used in accordance to the iOS HIG, which prefers a tab bar to support a flat information architecture {% include c.html r=6 a=false p="49" %}.  The tab icons were taken from [the NounProject](https://thenounproject.com), and used with permission.

##### Onboarding

When a user launches the application for the first time after downloading they're greeted with the following onboarding tutorial:

<div class="wrapper__wider">
	<ol class="grid grid--2 grid--5@full">
		<li>{% include f.html f="onboarding_welcome" %}</li>
    <li>{% include f.html f="onboarding_gad" %}</li>
    <li>{% include f.html f="onboarding_tutorial" %}</li>
    <li>{% include f.html f="onboarding_reminders" %}</li>
    <li>{% include f.html f="onboarding_done" %}</li>
	</ol>
</div>

Onboarding tutorials like this are a kind of gray area in iOS app design.  At best, they provide a clearer starting point for new users than, say, an empty screen; at worst, they force the user to read fluffy marketing text and/or sign up for a service before they can begin using the application.  Apple seems divided on the issue as well, advising designers to "think carefully before providing an onboarding experience" {% include c.html r=6 p="36" %}.  I heeded their advice and decided a brief instruction screen would offer a better springboard for guided recovery than the default screen (the Relax tab).

The tutorial was designed with Apple's guidelines in mind. Specifically, the HIG instructs:

* ###### "Give users only the information they need to get started" {% include c.html r=6 a=false y=false p="38" %}  
The screens included in the final application were deemed most important for first launch.  A brief description of GAD ({% include fr.html f="onboarding_gad" %}) was included after the welcome slide to provide a clear understanding of the disorder and who might be affected.  Next, an explanation of the application's three main tabs and how to use them was displayed ({% include fr.html f="onboarding_tutorial" %}). The daily reflection reminder preference wasn't shown here, set to a reasonable default of 8p.m. instead, while the relaxation reminder -- which ideally would be set to the user's normal waking time -- felt more individualized so it was shown in the second to last slide ({% include fr.html f="onboarding_reminders" %}). The last slide contained some final words of encouragement, and a button to dismiss the tutorial ({% include fr.html f="onboarding_done" %}).
* ###### "Use animation and interactivity to engage users and help them learn by doing" {% include c.html r=6 a=false p="38" %}  
Admittedly, the onboarding tutorial falls short from a user engagement perspective.  Given more time, some slides could certainly benefit from additional interactivity, especially the one shown in {% include fr.html f="onboarding_tutorial" %} which a user might reasonably skip due to its intimidating length.  In any case, the tutorial itself is interactive, using the recommended page control {% include c.html r=6 a=false y=false p="49" %} to allow users to swipe back and forth between slides.
* ###### "Make it easy to dismiss or skip the onboarding experience" {% include c.html r=6 a=false y=false p="39" %}  
Apple encourages developers to remember whether a user has viewed the onboarding tutorial to ensure it's only displayed once.  This was implemented during the development phase of the application.

Once the user reaches the final slide of the tutorial and taps the "Get Started" button, the tutorial is dismissed and they can begin exploring the application.

##### Learn tab

This tab ({% include fr.html f="learn" %}) represents the first core feature from the section above: reading materials.  There are two UI elements on this screen: a button to re-launch the instructions slide from the onboarding tutorial ({% include fr.html f="onboarding_tutorial" %}) and a table view listing of the available readings. The readings are excerpts from [Bourne](#reference-0) and the [National Institute of Mental Health](#reference-3).  When a user taps one of the available readings ({% include fr.html f="learn_tap" %}), an expanded reading view opens ({% include fr.html f="reading" %}). As the user scrolls to begin reading, the navigation bar and status bar disappear to support a full-screen presentation ({% include fr.html f="reading_scrolled" %}).  These elements reappear when the user scrolls back up, allowing him/her to return to use the standard navigation buttons to return to the Learn tab.

<div class="wrapper__wide">
	<ol class="flow">
		<li>{% include f.html f="learn_tap" %}</li>
		<li>{% include f.html f="reading" %}</li>
    <li>{% include f.html f="reading_scrolled" %}</li>
	</ol>
</div>

The background color of this tab is light blue, chosen for its calming properties {% include c.html r=4 %} and suitability for dark foreground text.

##### Relax tab

This tab represents the second core feature from the section above.  Because of its importance, this tab is selected by default when the user launches the application (except in certain situations). The background color of this tab is a vibrant blue, chosen for its relaxing properties {% include c.html r=4 %} and to distinguish between the lighter blue of the Learn tab.

There are two UI elements on this screen: a notification icon at the top and a mood picker in the middle.  The icon was placed at the top because the tab bar occupies the bottom (an iOS convention) and because this seemed to align with Apple's placement of similar controls, as seen with the "Scheduled" icon in Apple's Reminders application ({% include fr.html f="reminders_app" %}):

{% include f.html f="reminders_app" %}

When tapped ({% include fr.html f="relaxation_reminder_tap" %}), the reminder icon opens the view in {% include fr.html f="relaxation_reminder" %}, which lets the user toggle the daily relaxation reminder and change its time.  Changes to these settings are saved automatically, so this view can be dismissed by tapping anywhere else on the screen.

<div class="wrapper__wide">
	<ol class="flow">
		<li>{% include f.html f="relaxation_reminder_tap" %}</li>
		<li>{% include f.html f="relaxation_reminder" %}</li>
	</ol>
</div>

The mood picker is the primary focus of this screen, as it allows the user to begin the relaxation process.  The picker consists of three buttons, labeled with appropriate Emoji characters to represent the various moods a user might identify with.  Once the user selects one ({% include fr.html f="mood_tap" %}), a similar view appears underneath for him/her to determine the duration of their relaxation session. When the duration is selected ({% include fr.html f="duration_tap" %}), an appropriate relaxation exercise -- or sequence of exercises, depending on the duration chosen -- appears ({% include fr.html f="calming_scene" %}) and the user can begin relaxing.

<div class="wrapper__wide">
	<ol class="flow">
		<li>{% include f.html f="mood_tap" %}</li>
		<li>{% include f.html f="duration_tap" %}</li>
    <li>{% include f.html f="calming_scene" %}</li>
	</ol>
</div>

There are four relaxation exercises included in this application.  Depending on the user's choice of mood and duration, a relaxation session can consist of 1-3 exercises.  Each exercise has instructions at the top and a progress button at the bottom; if the current exercise is the only or final exercise in the sequence, this button is labelled "Done" and tapping it will return to the Relax tab.  Otherwise, this button is labelled "Next" and tapping it advances to the next exercise.  The relaxation exercises are determined in accordance with the guidelines from Bourne {% include c.html r=0 a=false %}, discussed in detail below:

<ol class="numbered-list figure--iPhone">
	<li>
		<h6>Calming scene exercise</h6>
		<p>This exercise is prioritized for less anxious moods, and as such was designed to convey a more playful, lighthearted attitude.  It displays a full-screen looping video of a calming landscape which pans automatically if the user tilts their device left or right.  The user can also swipe left or right to change to any of the 5 included landscapes, and the application will remember which one they viewed last to display the next time they use the exercise.</p>
		{% include f.html f="calming_scene_exercise" %}
		<p>The instruction text will fade out automatically after a brief interval, but the user can tap anywhere on the screen to make it reappear if desired.</p>
	</li>
	<li>
		<h6>Deep breathing exercise</h6>
		<p>This exercise is prioritized for more anxious states, driven by a single button that guides the user through a deep abdomen breathing procedure.  When the user first taps the "Begin" button, the button's label changes to instructions while the button itself grows or shrinks as an additional visual aid.</p>
		<ol class="flow">
			<li>{% include f.html f="deep_breathing" %}</li>
			<li>{% include f.html f="deep_breathing_tap" %}</li>
			<li>{% include f.html f="deep_breathing_started" %}</li>
		</ol>
		<p>The user can pause the exercise by tapping on the button again. The instruction text functions the same as in the Calming Scene exercise, disappearing automatically and reappearing on tap.</p>
	</li>
	<li>
		<h6>Coping statements exercise</h6>
		<p>This is the simplest yet most beneficial exercise for anxious mental states.  It displays a list of coping statements, taken mostly from Bourne {% include c.html r=0 a=false p="417-418" %}, that the user is encouraged to mentally repeat to create a feeling of acceptance, understanding that the instinct to resist an anxious episode only makes it more unpleasant.  The user can scroll this list freely and focus on any statement that he/she finds most relevant.</p>
		{% include f.html f="coping_statements_exercise" %}
		<p>Due to its importance in these scenarios, it's always the first exercise whenever the user chooses the most anxious mood in the picker.</p>
	</li>
	<li>
		<h6>Guided meditation exercise</h6>
		<p>This exercise is prioritized for the least anxious moods, as it likely requires the most focus and may not yield as immediate results as the other exercises.  Like the breathing exercise, it consists of a single button to play a guided 10-minute meditation recording.</p>
		<ol class="flow">
			<li>{% include f.html f="guided_meditation" %}</li>
			<li>{% include f.html f="guided_meditation_tap" %}</li>
			<li>{% include f.html f="guided_meditation_started" %}</li>
		</ol>
		<p>If the recording is already playing, the button can be used to pause playback, and vice-versa. The instruction text in this exercise behaves exactly the same as in the deep breathing exercise.</p>
	</li>
</ol>

##### Reflect tab

This tab represents the final core feature: positive psychology to create a long-term shift towards relapse prevention and positivity.  This tab uses a vibrant green background color, chosen for its calming properties {% include c.html r=4 %} and to differentiate between the Relax tab.

There are three main UI elements on this screen: a notification icon at the top, a compose button in the middle, and a timeline view below. The former works identically to the icon in the Relax tab, allowing the user to configure the daily reflection reminder:

<div class="wrapper__wide">
	<ol class="flow">
		<li>{% include f.html f="reflection_reminder_tap" %}</li>
		<li>{% include f.html f="reflection_reminder" %}</li>
	</ol>
</div>

The compose button is the primary focus on this screen. When tapped ({% include fr.html f="reflect_tap" %}), it opens the New Reflection screen ({% include fr.html f="new_reflection" %}) and lets the user log a positive event at any point during the day.  New events are added to the top of the timeline ({% include fr.html f="reflection_added" %}), which groups the last month's reflections in reverse chronological order by day.  The button itself uses the standard iOS compose icon found in Apple's own Mail application.

<div class="wrapper__wider">
	<ol class="flow">
		<li>{% include f.html f="reflect_tap" %}</li>
		<li>{% include f.html f="new_reflection" %}</li>
		<li>{% include f.html f="new_reflection_done" %}</li>
		<li>{% include f.html f="reflection_added" %}</li>
	</ol>
</div>

The timeline is a customized table view, following Apple's aforementioned recommendation, and can be scrolled freely to view previous reflections.

### Development

I developed this prototype with the latest version of Xcode 6.3 (with Swift 1.2) and iOS SDK 8.3. I had no experience with Swift or iOS development prior to this project, but I was able to find pre-made packages for many interactions and components and the Swift language was approachable (compared to Objective-C) coming from Javascript. 

## Testing

After the prototype was developed, user testing was conducted to measure its ease of use. Participants were solicited from a local college's PSY 100 participant pool after receiving permission from the ethical review board. Two sessions of 4 participants -- 8 participants total -- were needed with no further prerequisites for participation.  Participants received 1 research credit in exchange for their participation in the study.

### Method

These studies were carried out in an individualized – rather than traditional focus group – format. Participants were assigned a 15-minute block within the study’s allocated time so that each participant could receive equal attention from the researcher. All participants were first given an informed consent form and a brief description of the application they’d be testing.  They were then assigned an identification number and given an iPhone (provided by the researcher) with the application pre-installed.  They were asked to first interact with the application naturally without a specific goal in mind. Afterwards, they were prompted verbally to act out a variety of scenarios:

1. You go to bed at 10:00 p.m. and want to be reminded to reflect then
1. You’re feeling really stressed and you want to relax but don’t have much time
1. You forgot how you’re supposed to use each of the tabs
1. Something good just happened to you and you want to write it down
1. You notice self-talk patterns and want to read more about them
1. You wake up at different times every day so you don’t want to be reminded to relax
1. You woke up in a good mood but you want to relax for just a little bit
	1. You want to look at a different scene

Participants were encouraged to work through these tasks at their own pace, and none took longer than the allocated 15 minutes. They were invited to voice any suggestions, criticisms, or other feedback during this time, all of which were compiled and selectively incorporated into the application after the studies were complete.  At the end of the study, participants were encouraged to ask any final questions or voice final concerns before being given a full explanation of the application and its intended use and audience.  Before leaving, they were thanked for their participation and given a final debriefing form.

### Results

User feedback from these studies was largely positive. None of the eight testers encountered any obstacles or bugs they couldn't overcome on their own, and few voiced concerns after their evaluations.  Many users expressed sincere support for the project, asking when it would be available for public download so they could recommend it to a friend or family member.  For sake of completeness, all the (unedited) notes taken during these user studies can be found [here](public/studies.pdf){:target="_blank"}.

#### Modifications

Despite the overall positive experiences, there were a few minor stumbling blocks nearly every user seemed to run into during their tests, knowingly or unknowingly.

<ol class="numbered-list figure--iPhone">
	<li>
		<h5>"Set Reminder" button in onboarding</h5>
		<p>Only two of the eight users tapped the "Set Reminder" button from the daily relaxation reminder slide shown in {% include fr.html f="onboarding_reminders" %}.  The intended flow of this screen was:</p>
		<ol>
			<li>User chooses relaxation reminder time using the time picker</li>
			<li>User taps "Set Reminder" button to create the reminder</li>
		</ol>
		<p>From observing the users' behavior, however, the second step seemed redundant; as the relaxation reminder is created anyway, any time the user picks on this screen should be used without the additional confirmation step.  The "Set Reminder" button was therefore removed, and the functionality of the date picker was tweaked to configure the reminder automatically.</p>
		<ol class="flow flow--diagram">
			<li>{% include f.html f="onboarding_reminders_before" %}</li>
			<li>{% include f.html f="onboarding_reminders_after" %}</li>
		</ol>
	</li>
	<li>
		<h5>Larger text button hit areas</h5>
		<p>Many users "missed" some of the text-only buttons – "Get Started" in {% include fr.html f="onboarding_done" %}, "Next"/"Done" in any of the relaxation exercises, etc. – so the tappable area of these buttons was increased by <code>15pt</code> on each side.  This change is invisible to the users, but should result in fewer mis-taps.</p>
	</li>
	<li>
		<h5>Taps inside reminder views</h5>
		<p>In trying to enable or disable a reminder using the toggle switch ({% include fr.html f="reflection_reminder" %}), some users inadvertently closed the view entirely.  This occurred because any taps in this view outside of the switch or date picker were improperly configured to dismiss the view.  This has been corrected; only taps outside the reminder view can dismiss it now.</p>
	</li>
</ol>

## Conclusion

The goal of this project was to explore GAD treatment options and attempt to synthesize them into an iPhone application to offer a guided, comprehensive recovery program for GAD. I learned a great deal about anxiety disorder, iOS app design, user testing, and project management over the course of this exercise, and for that reason I feel it was successful.

### Future work

I saw opportunities for new features or additional refinements throughout the process:

{:.numbered-list}
1. ##### More engaging onboarding experience
   I didn't feel I had enough time to craft the truly engaging, interactive onboarding experience that Apple strongly recommends in the iOS HIG.  I've not yet determined what such an experience might entail, but I'm confident I could make noticeable improvements to the final version of the tutorial with some additional time.
1. ##### Password-protected Reflect tab
   Given the sensitive nature of this application, I originally planned to provide the option for a password-protected lock screen upon launch, though ultimately I reasoned the only sensitive data is in the timeline of the Reflect tab.  I think many users might feel a greater sense of security from such a feature.
1. ##### Relax tab improvements
   I was hesitant to muddle the Relax tab in any way, but I feel some positive reinforcement would be a nice touch to encourage consistent daily relaxation.  The aforementioned <a href="http://headspace.com">Headspace</a> meditation application, for example, uses streaks to motivate users to practice consistently, and <a href="http://snapchat.com/">Snapchat</a> uses them with <a href="http://www.thisisinsider.com/teens-are-obsessed-with-snap-streaks-on-snapchat-2016-12">devious success</a>. A similar feature seems appropriate for this tab, though it'd be important to retain ease of use as well.

In closing, I'd like to sincerely thank everyone who offered their support to this project. It was a terrific exercise, and I learned a lot.