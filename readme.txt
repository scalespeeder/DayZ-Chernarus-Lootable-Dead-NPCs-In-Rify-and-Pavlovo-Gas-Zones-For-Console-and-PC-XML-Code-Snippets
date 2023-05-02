DayZ Spawn NPC's In The Gas On Chernarus At Rify & M B Pavlovo Mod For Consoles & PC XML Snippets Instructions & Terms Of Use

These snippets, when inserted into the relevant files & / or uploaded to your Mission Server, will spawn in NPC's in the Toxix Gas at MB Pavlovo & Rify,
where they should die (killed by infected), to give real survivors a bit of a surprise & some good loot.

Limited Testing on PC Chernarus Local Server DAYZ Version 1.20 May 2023.

XML Files Created by @scalespeeder . Please report bugs & errors to scalespeeder@gmail.com with screenshots.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded xml / json files and instructions could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded files neccessitates increased regular restarts to prevent server crashing.

It is suggested you thoroughly test your server after applying these files to ensure proper
functioning of your server.

I always recomend you validate your files at: https://www.xmlvalidation.com/ and https://jsonformatter.curiousconcept.com/

To download all of the files from the Github, click on the green "Code" button then "download zip" and extract / unzip that file onto your local PC hard-drive.

Instructions:

Add these xml snippets to your types.xml:

<!-- start of gas npc types -->

  <type name="SurvivorM_Mirek">
        <nominal>0</nominal>
        <lifetime>1800</lifetime>
        <restock>0</restock>
        <min>1</min>
        <quantmin>-1</quantmin>
        <quantmax>-1</quantmax>
        <cost>100</cost>
        <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0"/>
    </type>
	
	  <type name="SurvivorM_Denis">
        <nominal>0</nominal>
        <lifetime>1800</lifetime>
        <restock>0</restock>
        <min>1</min>
        <quantmin>-1</quantmin>
        <quantmax>-1</quantmax>
        <cost>100</cost>
        <flags count_in_cargo="0" count_in_hoarder="0" count_in_map="1" count_in_player="0" crafted="0" deloot="0"/>
    </type>

<!-- end of gas npc types -->

Add these xml snippets to your cfgspawnabletypes.xml:

<!-- start of gas npc cfgspawnabletypes -->

<type name="SurvivorM_Mirek">
    <attachments>
        <item name="AirborneMask" />
    </attachments>
	<attachments>
        <item name="NBCHoodGray" />
    </attachments>
    <attachments>
        <item name="NBCJacketGray" />
    </attachments>
    <attachments>
        <item name="BDUPants" />
    </attachments>
    <attachments>
        <item name="MilitaryBoots_Black" />
    </attachments>
    <attachments>
        <item name="PlateCarrierVest_Camo" />
    </attachments>
    <attachments>
        <item name="NylonKnifeSheath" />
    </attachments>
    <attachments>
        <item name="GasMask_Filter_Improvised" />
    </attachments>
    <attachments>
        <item name="AliceBag_Black" />
    </attachments>
    <attachments>
        <item name="TacticalGloves_Beige" />
    </attachments>
    <attachments>
        <item name="MilitaryBelt" />
    </attachments>
<attachments>
        <item name="M4A1_Green" />
    </attachments>
    <attachments>
        <item name="M4_CQBBttstck" />
    </attachments>
    <attachments>
        <item name="M4_RISHndgrd_Green" />
    </attachments>
    <attachments>
        <item name="M4_Suppressor" />
    </attachments>
    <attachments>
        <item name="ACOGOptic" />
    </attachments>
    <attachments>
        <item name="Mag_STANAGCoupled_30Rnd" />
    </attachments>
    <attachments>
        <item name="FNX45" />
    </attachments>
    <attachments>
        <item name="Mag_FNX45_15Rnd" />
    </attachments>
    <attachments>
    <attachments>
        <item name="BloodTestKit" />
    </attachments>
    <attachments>
        <item name="Bandage" />
    </attachments>
    <attachments>
        <item name="Rice" />
    </attachments>
    <attachments>
        <item name="SodaCan_Cola" />
    </attachments>
</type>

<type name="SurvivorM_Denis">
    <attachments>
        <item name="NBCHoodYellow" />
    </attachments>
	<attachments>
        <item name="GP5GasMask" />
    </attachments>
    <attachments>
        <item name="NVGHeadstrap" />
    </attachments>
    <attachments>
        <item name="BDUJacket" />
    </attachments>
    <attachments>
        <item name="NBCPantsYellow" />
    </attachments>
    <attachments>
        <item name="NBCBootsGray" />
    </attachments>
    <attachments>
        <item name="UKAssVest_Camo" />
    </attachments>
    <attachments>
        <item name="NylonKnifeSheath" />
    </attachments>
    <attachments>
        <item name="GasMask_Filter" />
    </attachments>
    <attachments>
        <item name="AliceBag_Camo" />
    </attachments>
    <attachments>
        <item name="TacticalGloves_Beige" />
    </attachments>
    <attachments>
        <item name="MilitaryBelt" />
    </attachments>
<attachments>
        <item name="FAL" />
    </attachments>
    <attachments>
        <item name="Fal_OeBttstck" />
    </attachments>
    <attachments>
        <item name="Mag_FAL_20Rnd" />
    </attachments>
    <attachments>
        <item name="Mag_FAL_20Rnd" />
    </attachments>
    <attachments>
        <item name="FNX45" />
    </attachments>
    <attachments>
        <item name="Mag_FNX45_15Rnd" />
    </attachments>
    <attachments>
        <item name="BloodTestKit" />
    </attachments>
    <attachments>
        <item name="Bandage" />
    </attachments>
    <attachments>
        <item name="Rice" />
    </attachments>
    <attachments>
        <item name="SodaCan_Cola" />
    </attachments>
</type>

<!-- end of gas npc cfgspawnabletypes -->

Add these xml snippets to your events.xml:

<!-- start of gas npc events -->

<event name="ItemNPC1">
    <nominal>1</nominal>
    <min>0</min>
    <max>0</max>
    <lifetime>2500</lifetime>
    <restock>0</restock>
    <saferadius>0</saferadius>
    <distanceradius>0</distanceradius>
    <cleanupradius>200</cleanupradius>
	<secondary>InfectedNBC</secondary>
    <flags deletable="0" init_random="0" remove_damaged="1"/>
    <position>fixed</position>
    <limit>child</limit>
    <active>1</active>
    <children>
        <child lootmax="0" lootmin="0" max="3" min="1" type="SurvivorM_Mirek"/>
    </children>
</event>

<event name="ItemNPC2">
    <nominal>1</nominal>
    <min>0</min>
    <max>0</max>
    <lifetime>2500</lifetime>
    <restock>0</restock>
    <saferadius>0</saferadius>
    <distanceradius>0</distanceradius>
    <cleanupradius>200</cleanupradius>
	<secondary>InfectedNBC</secondary>
    <flags deletable="0" init_random="0" remove_damaged="1"/>
    <position>fixed</position>
    <limit>child</limit>
    <active>1</active>
    <children>
        <child lootmax="0" lootmin="0" max="3" min="1" type="SurvivorM_Denis"/>
    </children>
</event>

<!-- end of gas npc events -->

Add these code snippets to your cfgeventspawns.xml:


<!-- start of gas npc cfgeventspawns -->

	<!--rify npc-->
	<event name="ItemNPC1">
	<zone smin="1" smax="3" dmin="3" dmax="5" r="5" />
        <pos x="13844.078125" z="11201.705078125" a="113.000000" /> 
		<pos x="13763.6767578125" z="11199.7294921875" a="113.000000" />
		<pos x="13771.1708984375" z="11154.119140625" a="113.000000" />
		<pos x="13895.900390625" z="11193.599609375" a="113.000000" />
    </event>
	
	<!--pavlovo npc-->
	<event name="ItemNPC2">
	<zone smin="1" smax="3" dmin="3" dmax="5" r="5" />
        <pos x="2135.501953125" z="3331.018798828125" a="113.000000" /> 
		<pos x="2127.14453125" z="3372.369140625" a="113.000000" />
		<pos x="2147.824462890625" z="3286.78125" a="113.000000" />
		<pos x="2104.207275390625" z="3315.2177734375" a="113.000000" />
    </event>

<!-- end of gas npc cfgeventspawns -->

Save & re-start your server for the changes to take effect.

Thanks, Rob.