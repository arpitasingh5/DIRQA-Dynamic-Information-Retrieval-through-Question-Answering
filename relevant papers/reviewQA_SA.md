Mostly models for qa work on long text or short text
They work better on short texts
But mscqa ka model has combined those to and made it possible for only 1 model to be able to good at both  and also most of long text models work slow toh training speed bhi badhai about 1.5x. 

Its a multi step process to find an answer
So they have action and states there , where there are 2 non terminal states and 1 terminal state
1. If its a direct question which has a direct answer
2. Sentence selection which looks at the most top related answers based on a cnn
3. They take out the false positive answer which may look like answers in step 2 but are not.
Then after which this is run in multiple steps mostly they have and answer in max 3-4 steps in long text and 1-2 in short text
Improvements they have suggested is if there can be any more states which can essentially reduce the no. Of steps taken to find an answer based on an action generator which decided which step to be taken next.

<br></br>
<b> Reviewed by Gaurav Sinha(gauravsinha952@gmail.com) and  Arpita Singh (arpita5572@gmail.com) </b>
