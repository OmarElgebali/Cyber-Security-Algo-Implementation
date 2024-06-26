# Monoalphabetic Technique

### Test Cases
```csharp
string mainPlain = "meetmeafterthetogaparty";
string mainCipher = "phhwphdiwhuwkhwrjdsduwb".ToUpper();
string mainKey = "defghijklmnopqrstuvwxyzabc";
Regex regex = new Regex("d.{3}hijk.{4}p.rs.u.w.{4}b.");

string mainPlain1 = "abcdefghijklmnopqrstuvwxyz";
string mainCipher1 = "isyvkjruxedzqmctplofnbwgah".ToUpper();
string mainKey1 = "isyvkjruxedzqmctplofnbwgah";

string mainPlain2 = "hellosecuritymonoalphabetic";
string mainCipher2 = "ukzzcokynlxfaqcmciztuiskfxy".ToUpper();
string mainKey2 = "isyvkjruxedzqmctplofnbwgah";
Regex regex2 = new Regex("isy.k.{2}ux.{2}zqmct.lofn.{3}a.");

string mainPlain3 = "ENGLISHASTRONOMERWILLIAMLASSELLDISCOVEREDTRITON".ToLower();
string mainCipher3 = "EGSDAMTUMOLHGHFELWADDAUFDUMMEDDVAMIHQELEVOLAOHG".ToUpper();
string mainKey3 = "UNIVERSTABCDFGHJKLMOPQWXYZ".ToLower();
Regex regex3 = new Regex("u.ive.sta.{2}dfgh.{2}lmo.qw.{3}");

// Used for only FreqAnalysis (Match with >= 70%)
string largePlain =  "JULYPREVIOUSMONTHNEXTMONTHMEMBERSUPDATEFIRSTSCREENEDITORIALBACKONMYSOAPBOXWHYISITTHATUSEOFTHEENGLISHLANGUAGEISGETTINGSOVERYSLOPPYHOWLONGAGOWASITWHENGRAMMARCEASEDTOBEANESSENTIALELEMENTOFWRITINGADECENTESSAYAWHILEAGOTHEREWASACAMPAIGNTODOAWAYWITHTHEABERRANTAPOSTROPHENOWITSEEMSWENEEDANEWCAMPAIGNTOCONTENDWITHTHEABERRANTHYPHENYESIKNOWTHEREISAVASTDIFFERENCEBETWEENABLACKCABDRIVERANDABLACKCABDRIVERBUTNONEOFMYREFERENCEBOOKSINVITESHYPHENATIONOFBLACKCABORDRIVERANEXTREMEEXAMPLEPERHAPSBUTIMGETTINGTIREDOFSORTINGOUTHYPHENATEDWORDSANDREPLACINGTHEHYPHENWITHACOMMAORSEMICOLONORCREATINGANEWSENTENCENOOFCOURSEIMNOTPERFECTNOONEISBUTINOTONLYABHORTHEINAPPROPRIATEUSEOFAHYPHENIALSORECOGNISEASPLITINFINITIVEWHENISEEONEITMAYBEACCEPTABLEFORTHESTARSHIPENTERPRISETOBOLDLYGOBUTIDONOTTHINKTHATLOCALORGANISATIONSSHOULDBEENCOURAGEDTOPROACTIVELYENGAGEDEPARTMENTOFWORKANDPENSIONSPRESSRELEASEIRELYONJULIETOCHECKTHEPROOFCOPYOFUPDATEBEFOREYOUSEEITANDSHEWONTLETCARELESSUSEOFGRAMMARSLIPTHROUGHOOPSISHOULDNOWSAYIUSEDTORELYONJULIEASIWROTETHATBEFORESHEHANDEDINHERNOTICENOBEFOREYOUASKIDONTTHINKITWASANYTHINGISAIDORDIDSPECIFICALLYASMANYREADERSWILLKNOWADSETPROVIDEDOFFICESPACEFORTHEADMINISTRATIONFUNCTIONSOFNAEGAWITHJULIEWORKINGFORNAEGAFORTWELVEHOURSAWEEKINTHATSPACETHATCONTRACTCAMETOANABRUPTENDINMAYANDICANNOTFINDWORKWITHINTHEADSETSETUPTOMAKEUPTHOSEMISSINGHOURSSORATHERTHANTRYTOFINDASECONDPARTTIMEJOBJULIEHASFOUNDHERSELFFULLTIMEWORKSHEWILLBEGREATLYMISSEDNOTLEASTFORHERABILITYTOSPOTANABERRANTHYPHENORAPOSTROPHECHANGESAREAFOOTWELLTHEYWOULDHAVETOBEWOULDNTTHEYDAWNYESTHEONEWHOWRITESTHEFUNNYCOMMENTSINUPDATEWILLBETAKINGOVERJULIESJOBOFTHENEWSPAPERSTHETIMINGISRIGHTASHERYOUNGESTSTARTSFULLTIMESCHOOLINSEPTEMBERRUTHWARNERWHOMMANYOFYOUALREADYKNOWASADSETSDATAMANAGERALSOINCONTROLOFTHEWEBSITEWILLBETAKINGOVERASMEMBERSHIPSECRETARYASFORHELPINTHEOFFICEIMINTERVIEWINGFOURPEOPLETOMORROWANDEXPECTTOBEABLETOAPPOINTONEOFTHEMTOSTARTONAUGUSTTHATGIVESHERTHEYAREALLFEMALETHREEWEEKSTOFINDHERFEETBEFOREIGOONHOLIDAYFORAWEEKINEVERTHOUGHTTHATIDBEBLESSINGMOBILEPHONESBUTITHINKTHATITMIGHTBENEEDEDANDTHEFAMILYWILLFORONCEHAVETOACCEPTITTHEWIDERWORLDTHELSCHASBEENTAKINGABITOFAHAMMERINGTHISMONTHWITHTHEASSOCIATIONOFCOLLEGESSTILLASSERTINGTHATTHEREARECLEARTENSIONSBETWEENTHECENTREANDTHEARMSANDINSTITUTEOFDIRECTORSSAYINGTHATTHEORGANISATIONHASMADELITTLEIFANYIMPACTONBUSINESSTHEFUNDINGOFLEARNINGANDTHEPEOPLEWHOUNDERTAKEITCONTINUESTODOMINATETHEEDUCATIONALPRESSWHILSTTHEPROVISIONOFADDITIONALMONEYUNDERTHECOMPREHENSIVESPENDINGREVIEWISWELCOMEDITSNOTENOUGHISITEVERITSEEMSTHETHEPOWERSTHATBEAREWAKINGUPTOTHEIDEATHATMAYBEJUSTMAYBEAIMINGFORAPAPERLESSSOCIETYWASNOTSUCHAGOODIDEAATLEASTNOTUNTILYOUCANBECERTAINOFBEINGABLETORETRIEVETHEINFORMATIONCREATEDWELCOMETONEWMEMBERSCAMBRIDGESHIREGRIDFORLEARNINGCONTACTLILYDAINTERTELLOGWOODMANAGEMENTCONSULTANTSLTDCONTACTVELMABENNETTTELDETAILSOFTHEWORKOFTHESETWOORGANISATIONSWILLBEPLACEDONTHEADSETWEBSITEJUSTASSOONASWEGETTHEMTOTOPOFPAGETOINDEXCIPDURGESCAUTIONONEMPLOYEERIGHTSREVIEWPATRICIAHEWITTSECRETARYOFSTATEFORTRADEANDINDUSTRYHASTODAYJULYLAUNCHEDAREVIEWOFTHEEMPLOYMENTRELATIONSACTTHEREVIEWWILLLOOKATCOMPULSORYTRADEUNIONRECOGNITIONMEASURESALTHOUGHCHANGESWILLBELIMITEDACCORDINGTOTHEDTITHECIPDEXPRESSESCAUTIONABOUTTHEINITIATIVEDIANESINCLAIRLEADPUBLICPOLICYADVISERRESPONDEDTHELAWISWORKINGWELLATTHEMOMENTANDISFINELYBALANCEDBETWEENEMPLOYERSANDEMPLOYEESFORINSTANCEMANYTRADEUNIONSARECURRENTLYWINNINGCLAIMSUNDERTHEACTWEHOPETHATTHEGOVERNMENTALLOWSTHISLEGISLATIONTOBEDDOWNBEFORECHANGESARECONSIDEREDTHEDTIHASALSOLAUNCHEDACONSULTATIONDOCUMENTTODAYONIMPLEMENTINGTHEEUDIRECTIVEONINFORMINGANDCONSULTINGSTAFFINTHEUKTHISISDUETOCOMEINTOEFFECTINTHEUKFORORGANISATIONSOFMORETHANSTAFFBYMARCHANDFORSMALLERORGANISATIONSBYMARCHORGANISATIONSEMPLOYINGLESSTHANPEOPLEARELIKELYTOBEEXCLUDEDCIPDPRESSRELEASEJULYTOTOPOFPAGETOINDEXJOHNSONHERALDSNEWERAFORBRITISHFIRMSNEWPROPOSALSTOCUTREDTAPEANDSAVESMALLBUSINESSESAROUNDMILLIONAYEARWEREUNVEILEDTODAYJULYWITHTHEPUBLICATIONOFTHEGOVERNMENTWHITEPAPERMODERNISINGCOMPANYLAWTHEWHITEPAPERREFLECTSTHECHANGESINTHEBUSINESSENVIRONMENTINRECENTYEARSPARTICULARLYTHEGROWTHOFSMALLBUSINESSESANDADVANCESINCOMMUNICATIONSTECHNOLOGYANDINCLUDESPLANSTOSIMPLIFYTHELAWANDREDUCEBURDENSONSMALLFIRMSIMPROVETRANSPARENCYTOINCREASECONFIDENCEINBUSINESSANDIMPROVEGOVERNANCETOENCOURAGEANDSUPPORTRESPONSIBLEBUSINESSOTHERKEYPROPOSALSINCLUDEDIRECTORSDUTIESWILLBESETOUTCLEARLYINSTATUTEFORTHEFIRSTTIMECORPORATEDIRECTORSWILLBEPROHIBITEDPRIVATECOMPANIESNOLONGERWILLHAVETOAPPOINTCOMPANYSECRETARIESPRIVATECOMPANIESNOLONGERWILLHAVETOHOLDAGMSUNLESSMEMBERSWANTTHEMCOMPANIESWILLBEABLETOEXPLOITTHEINTERNETANDEMAILTOMAKEDECISIONSCOMPANIESWILLHAVESIMPLERREPORTSANDACCOUNTSACCOUNTSWILLBEFILEDMOREQUICKLYWITHINSEVENMONTHSFORPRIVATECOMPANIESANDSIXMONTHSFORPUBLICCOMPANIESQUOTEDCOMPANIESWILLHAVETOPOSTREPORTSONWEBSITESBEFORETHISTHELARGESTCOMPANIESWILLPUBLISHANOPERATINGANDFINANCIALREVIEWCOMPANIESANDTHEIRDIRECTORSCONVICTEDOFFLOUTINGCOMPANYLAWCOULDBENAMEDINACENTRALREGISTERTHEWHITEPAPERISAVAILABLEONLINEATWWWDTIGOVUKCOMPANIESBILLASUMMARYOFTHEMEASURESOFPARTICULARINTERESTTOSMALLBUSINESSISALSOAVAILABLEDTIPRESSRELEASEPJULYTOTOPOFPAGETOINDEXCBIPRAISESCOMPANYLAWREFORMPLANSTHECONFEDERATIONOFBRITISHINDUSTRYCBIISBACKINGGOVERNMENTPROPOSALSTOREFORMCOMPANYLAWITISHOPEDTHATTHISWILLSIMPLIFYTHEREGIMEFORSMALLFIRMSWHILEIMPROVINGACCOUNTABILITYFORLARGEROGANISATIONSTHECBIISPRAISINGGOVERNMENTPLANSTOIMPLEMENTTHERECOMMENDATIONSOFTHECOMPANYLAWREVIEWITISHOPEDTHATTHISWILLMAKETHELAWCLEARERANDMOREEFFECTIVEHRLOOKJULYTOTOPOFPAGETOINDEXPATRICIAHEWITTANNOUNCESNEWAPPOINTMENTSTOTHESMALLBUSINESSCOUNCILSECRETARYOFSTATEFORTRADEANDINDUSTRYPATRICIAHEWITTTODAYJULYANNOUNCEDTHEFULLNEWMEMBERSHIPOFTHESMALLBUSINESSCOUNCILSBCTHEMEMBERSWORKWITHTHECHAIRMANWILLIAMSARGENTTOADVISETHEGOVERNMENTONISSUESAFFECTINGSMALLBUSINESSESTHESBCREPRESENTSAWIDERANGEOFSECTORSINCLUDINGMANUFACTURINGRETAILSOCIALENTERPRISETOURISMBUSINESSSUPPORTENVIRONMENTALBUSINESSESMEDIAANDENTERTAINMENTRECRUITMENTACCOUNTANCYANDACADEMIATHEMEMBERSHIPREPRESENTSALLPARTSOFTHEUKANDINCLUDESPEOPLEOFDIFFERENTAGESANDBACKGROUNDSDTIPRESSRELEASEPJULYUPDATECOMMENTTHEPRESSRELEASELISTSTHEPEOPLEWITHSHORTBIOGSANDSOMEOFTHEMREALLYAREFROMSMALLBUSINESSESTOTOPOFPAGETOINDEXSMALLBUSINESSSECTORGROWTHEQUIVALENTTOOVERNEWSTARTUPSEVERYDAYNIGELGRIFFITHSHAILSNETINCREASEINBUSINESSPOPULATIONNEWFIGURESPUBLISHEDTODAYJULYSHOWTHEREWASANETINCREASEOFMORETHANFIRMSOPERATINGINTHEUKINCOMPAREDTOTHEPREVIOUSYEAREQUIVALENTTOOVERNEWBUSINESSESSTARTINGUPEVERYDAYACCORDINGTONEWSTATISTICSFROMTHEDTISSMALLBUSINESSSERVICESBSTHEBUSINESSPOPULATIONTOTALLEDLASTYEARCOMPAREDTOINTHEYEAROTHERFINDINGSSHOWTHEREWEREMILLIONMOREBUSINESSESTHANINTHEFIRSTYEARFORWHICHCOMPARABLEFIGURESAREAVAILABLETHENUMBEROFMEDIUMSIZEDBUSINESSESREACHEDFORTHEFIRSTTIMEINSEVENYEARSANDATLEASTOFBUSINESSESINALLINDUSTRIESWERESMESTHEFULLSTATISTICSCANBEDOWNLOADEDFROMTHESMALLBUSINESSSERVICEWEBSITEATWWWSBSGOVUKSTATISTICSDTIPRESSRELEASEPJULYTHEGAMECOMESTIMATESTHATWORLDCUPABSENTEEISMCOSTTHEUKAROUNDMILLIONTHISFIGUREISONLYATENTHOFTHEPREDICTEDCOSTSINCEMANYEMPLOYERSWERECOOPERATIVEANDALLOWEDEMPLOYEESTOEITHERCHANGETHEIRHOURSORWATCHTHEMATCHESATWORKHOWEVEROFFANSSTILLADMITTEDTOTAKINGATLEASTONEDAYASSICKLEAVEIRSEMPLOYMENTREVIEWISSUEJULYTOTOPOFPAGETOINDEXCOMMUNICATIONSKILLSLACKINGATTHETOPACCORDINGTONEWRESEARCHFROMTHEAZIZCORPORATIONBRITAINSTOPBUSINESSLEADERSARELARGELYUNHEARDUNRECOGNISEDANDCONSIDEREDUNABLETOCOMMUNICATEEFFECTIVELYBYTHEIRBUSINESSPEERSTHERESEARCHREVEALEDTHATWHILEOFUKCOMPANYDIRECTORSCONSIDERUSBUSINESSEXECUTIVESTOHAVEANEXCELLENTORGOODMEDIAIMAGEANDREPUTATIONONLYBELIEVETHESAMEOFUKEXECUTIVESINADDITIONFEELTHATTHEMEDIAIMAGEOFTHEUKSLEADINGBUSINESSEXECUTIVESISINNEEDOFIMPROVEMENTTRAININGZONELEARNINGWIREISSUEJULYTOTOPOFPAGETOINDEXTHEHUMBLELEADERANARTICLEINBULLETPOINTJUNEISSUEARGUESTHATHAVINGALARGERTHANLIFECORPORATEHEROASALEADERCANBEDETRIMENTALTOANORGANISATIONTHEMAINCRITICISMSOFTHISTYPEOFLEADERARETHATTHEYARESELFSERVINGMOREINTERESTEDINSELFPROMOTIONANDCELEBRITYTHANTEAMWORKTHEARTICLEFURTHERSUGGESTSTHATINMANYCASESTHEYFAILTOADDVALUEDONOTDELIVERSUSTAINABLERESULTSANDDONTWORKTOIMPROVEPERFORMANCETHEARTICLETELLSUSTHATTRULYTRANSFORMATIONALLEADERSHAVEANEQUALRATIOOFHUMILITYANDPROFESSIONALWILLTHEYAREABLEMANAGERSRATHERTHANAFGUREHEADFORTHEMEDIAANDCANENGENDEREMPLOYEETRUSTCOMMITMENTANDLOYALTYTHEYWILLALSOHAVEADESIRETOSHUNPUBLICITYCHANNELAMBTIONINTODEVELOPINGTHECOMPANYNOTTHEMSELVESGIVECREDITTOOTHERSAROUNDTHEMANDDESPISEMEDIOCRITYTOTOPOFPAGETOINDEXWHATAMESSPARTICPATIONASASMPLEMANAGERIALRULETOCOMPLEXIFYORGANISATIONSACTUALLYASERIOUSRESEARCHPAPERWHICHLOOKSATSOMEOFTHESIMPLERULESOFMANAGEMENTWHCHNTHEENDCANFOULUPOURLIVESFORGOODBUTONLYIFWELETTHEMWEALLIASSUMEKNOWOFTHEHORSEMADEBYACOMMITTEEINTODAYSCONSULTATIVECLMATEWECOULDBEHEADINGFORTRYINGTODEALINCAMELSUNLESSULTIMATELYTHEMANAGERIETHESINGLEPERSONRESPONSIBLEFORMAKINGANDIMPLEMENTNGTHEDECISIONDECIDESOURHORSESSHOULDNOTHAVEHUMPSWHETHERONEORTWOISIMMATERIALSOINTHEENDWEHAVETHEAUTOCRATICDICTATORIALVICTORIANPARENTWHOSEOFFSPRINGMIGHTIFDARINGTOQUESTIONRECEIVETHERESPONSEBECAUSEISAYITISJOURNALOFMANAGEMENTSTUDIESMARCHUPDATECOMMENTONTHEOTHERHANDTHEEUROPEANDIRECTIVESAYSTHOUSHALTCONSULTANDATLENGTHUNLESSTHEREARELESSTHANSTAFFINYOURORGANISATIONSORRYGUYSTHATMEANSTHATICANCONTINUETOBETHEAUTOCRATCDCTATORIALPARENTTYPEATLEASTINLAWIFNOTREALITYTOTOPOFPAGETOINDEXLEADERSNEEDMORETRAININGAYEARAFTERTHELIBRARYWORLDSRECRUTRETANANDLEADREPORTWARNEDOFFALLINGSTANDARDSINEXECUTIVEABILITYMUSEUMSAREFACINGASIMLARLEADERSHIPCRISISSPEAKINGATTHEANNUALMUSEUMDRECTORSCONFERENCELIZAMOSOFTHECOUNCILFOREXCELLENCEINMANAGEMENTANDLEADERSHIPTOLDDELEGATESTHATTHEYSHOULDHEEDTHEDSQUETBEINGVOICEDBYJUNIORANDMIDDLEMANAGERSINTHEPUBLICSECTORACCORDNGTOARECENTREPORTOFJUNIORANDMIDDLEMANAGERSCLAIMTHATLEADERSHPNTHEIRORGANISATIONISPOORMSAMOSBELIEVESTHATTHISMATTERSBECAUSEGOODLEADERSCANNSPIREANDENERGISETHEIREMPLOYEESWHICHHASAPOSTVEEFFECTONPERFORMANCELIBRARYANDINFORMATIONUPDATEJULYVOLTOTOPOFPAGETOINDEXPATHTOTHEGATEWAYISCLEAREDAYEARAGOANENTREPRENEURSEEKINGHELPTOSETUPACOMPANYINGLASGOWRISKEDBEINGKNOCKEDDOWNINARUSHOFAGENCIESBRANDISHINGMORETHANDIFFERENTSUPPORTPRODUCTSANDSERVICESNEWBUSINESSESFACEDABEWILDERINGCHOICEOFDIFFERENTPUBLICSECTORAGENCIESPROVIDINGACCESSTOOVERBUSINESSSUPPORTPARTNERSHPSMOSTLYKNOWNBYCONFUSINGTHREELETTERACRONYMSYETDESPITETHEWELTEROFSERVICESAVAILABLEWITHLITERALLYHUNDREDSOFADVISERSGRANTSANDTRAININGSCHEMESONOFFERRESEARCHSHOWEDTHATGLASGOWURGENTLYNEEDEDTOFINDBETTERWAYSTOIMPROVEITSBUSINESSBIRTHRATEANDITSINDIGENOUSCOMPANYSURVIVALRATETHEVULNERABILITYOFSMALLANDMEDIUMSIZEDENTERPRISESSMESTOFAILURENTHEIREARLYYEARSISCLEARANDINGLASGOWONLYOFSMESSURVIVELONGERTHANTHREEYEARSCOMPAREDTOTHENATIONALTHREEYEARSURVIVALRATEOFONTOPOFLOWERTHANAVERAGESURVIVALRATESGLASGOWALSOHADAPROBLEMWITHEUROPEANBUSINESSGRANTSBEINGLEFTUNCLAIMEDBECAUSEELIGIBLECOMPANESDDNOTAPPLYFORTHECASHONOFFERDUNCANTANNAHILLCHIEFEXECUTIVEOFGLASGOWCHAMBEROFCOMMERCESEZEDTHECHANCETOPOOLTHERESOURCESOFTHEPRIVATEANDPUBLCSECTORSINAMAJOREFFORTTOADDRESSTHESHORTCOMINGSOFTHESYSTEMANDCREATEASNGLEPOINTOFENTRYFORCOMPANIESSEEKNGHELPATANYSTAGEOFTHEIRDEVELOPMENTSMALLBUSINESSGATEWAYISATVALERIEDARROCHSCOTTISHHERALDJULYMYSCHOOLDAYSWERETHEHAPPESTDAYSOFMY".ToLower();
string largeCipher = "MXOBSUHYLRXVPRQWKQHAWPRQWKPHPEHUVXSGDWHILUVWVFUHHQHGLWRULDOEDFNRQPBVRDSERAZKBLVLWWKDWXVHRIWKHHQJOLVKODQJXDJHLVJHWWLQJVRYHUBVORSSBKRZORQJDJRZDVLWZKHQJUDPPDUFHDVHGWREHDQHVVHQWLDOHOHPHQWRIZULWLQJDGHFHQWHVVDBDZKLOHDJRWKHUHZDVDFDPSDLJQWRGRDZDBZLWKWKHDEHUUDQWDSRVWURSKHQRZLWVHHPVZHQHHGDQHZFDPSDLJQWRFRQWHQGZLWKWKHDEHUUDQWKBSKHQBHVLNQRZWKHUHLVDYDVWGLIIHUHQFHEHWZHHQDEODFNFDEGULYHUDQGDEODFNFDEGULYHUEXWQRQHRIPBUHIHUHQFHERRNVLQYLWHVKBSKHQDWLRQRIEODFNFDERUGULYHUDQHAWUHPHHADPSOHSHUKDSVEXWLPJHWWLQJWLUHGRIVRUWLQJRXWKBSKHQDWHGZRUGVDQGUHSODFLQJWKHKBSKHQZLWKDFRPPDRUVHPLFRORQRUFUHDWLQJDQHZVHQWHQFHQRRIFRXUVHLPQRWSHUIHFWQRRQHLVEXWLQRWRQOBDEKRUWKHLQDSSURSULDWHXVHRIDKBSKHQLDOVRUHFRJQLVHDVSOLWLQILQLWLYHZKHQLVHHRQHLWPDBEHDFFHSWDEOHIRUWKHVWDUVKLSHQWHUSULVHWREROGOBJREXWLGRQRWWKLQNWKDWORFDORUJDQLVDWLRQVVKRXOGEHHQFRXUDJHGWRSURDFWLYHOBHQJDJHGHSDUWPHQWRIZRUNDQGSHQVLRQVSUHVVUHOHDVHLUHOBRQMXOLHWRFKHFNWKHSURRIFRSBRIXSGDWHEHIRUHBRXVHHLWDQGVKHZRQWOHWFDUHOHVVXVHRIJUDPPDUVOLSWKURXJKRRSVLVKRXOGQRZVDBLXVHGWRUHOBRQMXOLHDVLZURWHWKDWEHIRUHVKHKDQGHGLQKHUQRWLFHQREHIRUHBRXDVNLGRQWWKLQNLWZDVDQBWKLQJLVDLGRUGLGVSHFLILFDOOBDVPDQBUHDGHUVZLOONQRZDGVHWSURYLGHGRIILFHVSDFHIRUWKHDGPLQLVWUDWLRQIXQFWLRQVRIQDHJDZLWKMXOLHZRUNLQJIRUQDHJDIRUWZHOYHKRXUVDZHHNLQWKDWVSDFHWKDWFRQWUDFWFDPHWRDQDEUXSWHQGLQPDBDQGLFDQQRWILQGZRUNZLWKLQWKHDGVHWVHWXSWRPDNHXSWKRVHPLVVLQJKRXUVVRUDWKHUWKDQWUBWRILQGDVHFRQGSDUWWLPHMREMXOLHKDVIRXQGKHUVHOIIXOOWLPHZRUNVKHZLOOEHJUHDWOBPLVVHGQRWOHDVWIRUKHUDELOLWBWRVSRWDQDEHUUDQWKBSKHQRUDSRVWURSKHFKDQJHVDUHDIRRWZHOOWKHBZRXOGKDYHWREHZRXOGQWWKHBGDZQBHVWKHRQHZKRZULWHVWKHIXQQBFRPPHQWVLQXSGDWHZLOOEHWDNLQJRYHUMXOLHVMRERIWKHQHZVSDSHUVWKHWLPLQJLVULJKWDVKHUBRXQJHVWVWDUWVIXOOWLPHVFKRROLQVHSWHPEHUUXWKZDUQHUZKRPPDQBRIBRXDOUHDGBNQRZDVDGVHWVGDWDPDQDJHUDOVRLQFRQWURORIWKHZHEVLWHZLOOEHWDNLQJRYHUDVPHPEHUVKLSVHFUHWDUBDVIRUKHOSLQWKHRIILFHLPLQWHUYLHZLQJIRXUSHRSOHWRPRUURZDQGHASHFWWREHDEOHWRDSSRLQWRQHRIWKHPWRVWDUWRQDXJXVWWKDWJLYHVKHUWKHBDUHDOOIHPDOHWKUHHZHHNVWRILQGKHUIHHWEHIRUHLJRRQKROLGDBIRUDZHHNLQHYHUWKRXJKWWKDWLGEHEOHVVLQJPRELOHSKRQHVEXWLWKLQNWKDWLWPLJKWEHQHHGHGDQGWKHIDPLOBZLOOIRURQFHKDYHWRDFFHSWLWWKHZLGHUZRUOGWKHOVFKDVEHHQWDNLQJDELWRIDKDPPHULQJWKLVPRQWKZLWKWKHDVVRFLDWLRQRIFROOHJHVVWLOODVVHUWLQJWKDWWKHUHDUHFOHDUWHQVLRQVEHWZHHQWKHFHQWUHDQGWKHDUPVDQGLQVWLWXWHRIGLUHFWRUVVDBLQJWKDWWKHRUJDQLVDWLRQKDVPDGHOLWWOHLIDQBLPSDFWRQEXVLQHVVWKHIXQGLQJRIOHDUQLQJDQGWKHSHRSOHZKRXQGHUWDNHLWFRQWLQXHVWRGRPLQDWHWKHHGXFDWLRQDOSUHVVZKLOVWWKHSURYLVLRQRIDGGLWLRQDOPRQHBXQGHUWKHFRPSUHKHQVLYHVSHQGLQJUHYLHZLVZHOFRPHGLWVQRWHQRXJKLVLWHYHULWVHHPVWKHWKHSRZHUVWKDWEHDUHZDNLQJXSWRWKHLGHDWKDWPDBEHMXVWPDBEHDLPLQJIRUDSDSHUOHVVVRFLHWBZDVQRWVXFKDJRRGLGHDDWOHDVWQRWXQWLOBRXFDQEHFHUWDLQRIEHLQJDEOHWRUHWULHYHWKHLQIRUPDWLRQFUHDWHGZHOFRPHWRQHZPHPEHUVFDPEULGJHVKLUHJULGIRUOHDUQLQJFRQWDFWOLOBGDLQWHUWHOORJZRRGPDQDJHPHQWFRQVXOWDQWVOWGFRQWDFWYHOPDEHQQHWWWHOGHWDLOVRIWKHZRUNRIWKHVHWZRRUJDQLVDWLRQVZLOOEHSODFHGRQWKHDGVHWZHEVLWHMXVWDVVRRQDVZHJHWWKHPWRWRSRISDJHWRLQGHAFLSGXUJHVFDXWLRQRQHPSORBHHULJKWVUHYLHZSDWULFLDKHZLWWVHFUHWDUBRIVWDWHIRUWUDGHDQGLQGXVWUBKDVWRGDBMXOBODXQFKHGDUHYLHZRIWKHHPSORBPHQWUHODWLRQVDFWWKHUHYLHZZLOOORRNDWFRPSXOVRUBWUDGHXQLRQUHFRJQLWLRQPHDVXUHVDOWKRXJKFKDQJHVZLOOEHOLPLWHGDFFRUGLQJWRWKHGWLWKHFLSGHASUHVVHVFDXWLRQDERXWWKHLQLWLDWLYHGLDQHVLQFODLUOHDGSXEOLFSROLFBDGYLVHUUHVSRQGHGWKHODZLVZRUNLQJZHOODWWKHPRPHQWDQGLVILQHOBEDODQFHGEHWZHHQHPSORBHUVDQGHPSORBHHVIRULQVWDQFHPDQBWUDGHXQLRQVDUHFXUUHQWOBZLQQLQJFODLPVXQGHUWKHDFWZHKRSHWKDWWKHJRYHUQPHQWDOORZVWKLVOHJLVODWLRQWREHGGRZQEHIRUHFKDQJHVDUHFRQVLGHUHGWKHGWLKDVDOVRODXQFKHGDFRQVXOWDWLRQGRFXPHQWWRGDBRQLPSOHPHQWLQJWKHHXGLUHFWLYHRQLQIRUPLQJDQGFRQVXOWLQJVWDIILQWKHXNWKLVLVGXHWRFRPHLQWRHIIHFWLQWKHXNIRURUJDQLVDWLRQVRIPRUHWKDQVWDIIEBPDUFKDQGIRUVPDOOHURUJDQLVDWLRQVEBPDUFKRUJDQLVDWLRQVHPSORBLQJOHVVWKDQSHRSOHDUHOLNHOBWREHHAFOXGHGFLSGSUHVVUHOHDVHMXOBWRWRSRISDJHWRLQGHAMRKQVRQKHUDOGVQHZHUDIRUEULWLVKILUPVQHZSURSRVDOVWRFXWUHGWDSHDQGVDYHVPDOOEXVLQHVVHVDURXQGPLOOLRQDBHDUZHUHXQYHLOHGWRGDBMXOBZLWKWKHSXEOLFDWLRQRIWKHJRYHUQPHQWZKLWHSDSHUPRGHUQLVLQJFRPSDQBODZWKHZKLWHSDSHUUHIOHFWVWKHFKDQJHVLQWKHEXVLQHVVHQYLURQPHQWLQUHFHQWBHDUVSDUWLFXODUOBWKHJURZWKRIVPDOOEXVLQHVVHVDQGDGYDQFHVLQFRPPXQLFDWLRQVWHFKQRORJBDQGLQFOXGHVSODQVWRVLPSOLIBWKHODZDQGUHGXFHEXUGHQVRQVPDOOILUPVLPSURYHWUDQVSDUHQFBWRLQFUHDVHFRQILGHQFHLQEXVLQHVVDQGLPSURYHJRYHUQDQFHWRHQFRXUDJHDQGVXSSRUWUHVSRQVLEOHEXVLQHVVRWKHUNHBSURSRVDOVLQFOXGHGLUHFWRUVGXWLHVZLOOEHVHWRXWFOHDUOBLQVWDWXWHIRUWKHILUVWWLPHFRUSRUDWHGLUHFWRUVZLOOEHSURKLELWHGSULYDWHFRPSDQLHVQRORQJHUZLOOKDYHWRDSSRLQWFRPSDQBVHFUHWDULHVSULYDWHFRPSDQLHVQRORQJHUZLOOKDYHWRKROGDJPVXQOHVVPHPEHUVZDQWWKHPFRPSDQLHVZLOOEHDEOHWRHASORLWWKHLQWHUQHWDQGHPDLOWRPDNHGHFLVLRQVFRPSDQLHVZLOOKDYHVLPSOHUUHSRUWVDQGDFFRXQWVDFFRXQWVZLOOEHILOHGPRUHTXLFNOBZLWKLQVHYHQPRQWKVIRUSULYDWHFRPSDQLHVDQGVLAPRQWKVIRUSXEOLFFRPSDQLHVTXRWHGFRPSDQLHVZLOOKDYHWRSRVWUHSRUWVRQZHEVLWHVEHIRUHWKLVWKHODUJHVWFRPSDQLHVZLOOSXEOLVKDQRSHUDWLQJDQGILQDQFLDOUHYLHZFRPSDQLHVDQGWKHLUGLUHFWRUVFRQYLFWHGRIIORXWLQJFRPSDQBODZFRXOGEHQDPHGLQDFHQWUDOUHJLVWHUWKHZKLWHSDSHULVDYDLODEOHRQOLQHDWZZZGWLJRYXNFRPSDQLHVELOODVXPPDUBRIWKHPHDVXUHVRISDUWLFXODULQWHUHVWWRVPDOOEXVLQHVVLVDOVRDYDLODEOHGWLSUHVVUHOHDVHSMXOBWRWRSRISDJHWRLQGHAFELSUDLVHVFRPSDQBODZUHIRUPSODQVWKHFRQIHGHUDWLRQRIEULWLVKLQGXVWUBFELLVEDFNLQJJRYHUQPHQWSURSRVDOVWRUHIRUPFRPSDQBODZLWLVKRSHGWKDWWKLVZLOOVLPSOLIBWKHUHJLPHIRUVPDOOILUPVZKLOHLPSURYLQJDFFRXQWDELOLWBIRUODUJHURJDQLVDWLRQVWKHFELLVSUDLVLQJJRYHUQPHQWSODQVWRLPSOHPHQWWKHUHFRPPHQGDWLRQVRIWKHFRPSDQBODZUHYLHZLWLVKRSHGWKDWWKLVZLOOPDNHWKHODZFOHDUHUDQGPRUHHIIHFWLYHKUORRNMXOBWRWRSRISDJHWRLQGHASDWULFLDKHZLWWDQQRXQFHVQHZDSSRLQWPHQWVWRWKHVPDOOEXVLQHVVFRXQFLOVHFUHWDUBRIVWDWHIRUWUDGHDQGLQGXVWUBSDWULFLDKHZLWWWRGDBMXOBDQQRXQFHGWKHIXOOQHZPHPEHUVKLSRIWKHVPDOOEXVLQHVVFRXQFLOVEFWKHPHPEHUVZRUNZLWKWKHFKDLUPDQZLOOLDPVDUJHQWWRDGYLVHWKHJRYHUQPHQWRQLVVXHVDIIHFWLQJVPDOOEXVLQHVVHVWKHVEFUHSUHVHQWVDZLGHUDQJHRIVHFWRUVLQFOXGLQJPDQXIDFWXULQJUHWDLOVRFLDOHQWHUSULVHWRXULVPEXVLQHVVVXSSRUWHQYLURQPHQWDOEXVLQHVVHVPHGLDDQGHQWHUWDLQPHQWUHFUXLWPHQWDFFRXQWDQFBDQGDFDGHPLDWKHPHPEHUVKLSUHSUHVHQWVDOOSDUWVRIWKHXNDQGLQFOXGHVSHRSOHRIGLIIHUHQWDJHVDQGEDFNJURXQGVGWLSUHVVUHOHDVHSMXOBXSGDWHFRPPHQWWKHSUHVVUHOHDVHOLVWVWKHSHRSOHZLWKVKRUWELRJVDQGVRPHRIWKHPUHDOOBDUHIURPVPDOOEXVLQHVVHVWRWRSRISDJHWRLQGHAVPDOOEXVLQHVVVHFWRUJURZWKHTXLYDOHQWWRRYHUQHZVWDUWXSVHYHUBGDBQLJHOJULIILWKVKDLOVQHWLQFUHDVHLQEXVLQHVVSRSXODWLRQQHZILJXUHVSXEOLVKHGWRGDBMXOBVKRZWKHUHZDVDQHWLQFUHDVHRIPRUHWKDQILUPVRSHUDWLQJLQWKHXNLQFRPSDUHGWRWKHSUHYLRXVBHDUHTXLYDOHQWWRRYHUQHZEXVLQHVVHVVWDUWLQJXSHYHUBGDBDFFRUGLQJWRQHZVWDWLVWLFVIURPWKHGWLVVPDOOEXVLQHVVVHUYLFHVEVWKHEXVLQHVVSRSXODWLRQWRWDOOHGODVWBHDUFRPSDUHGWRLQWKHBHDURWKHUILQGLQJVVKRZWKHUHZHUHPLOOLRQPRUHEXVLQHVVHVWKDQLQWKHILUVWBHDUIRUZKLFKFRPSDUDEOHILJXUHVDUHDYDLODEOHWKHQXPEHURIPHGLXPVLCHGEXVLQHVVHVUHDFKHGIRUWKHILUVWWLPHLQVHYHQBHDUVDQGDWOHDVWRIEXVLQHVVHVLQDOOLQGXVWULHVZHUHVPHVWKHIXOOVWDWLVWLFVFDQEHGRZQORDGHGIURPWKHVPDOOEXVLQHVVVHUYLFHZHEVLWHDWZZZVEVJRYXNVWDWLVWLFVGWLSUHVVUHOHDVHSMXOBWKHJDPHFRPHVWLPDWHVWKDWZRUOGFXSDEVHQWHHLVPFRVWWKHXNDURXQGPLOOLRQWKLVILJXUHLVRQOBDWHQWKRIWKHSUHGLFWHGFRVWVLQFHPDQBHPSORBHUVZHUHFRRSHUDWLYHDQGDOORZHGHPSORBHHVWRHLWKHUFKDQJHWKHLUKRXUVRUZDWFKWKHPDWFKHVDWZRUNKRZHYHURIIDQVVWLOODGPLWWHGWRWDNLQJDWOHDVWRQHGDBDVVLFNOHDYHLUVHPSORBPHQWUHYLHZLVVXHMXOBWRWRSRISDJHWRLQGHAFRPPXQLFDWLRQVNLOOVODFNLQJDWWKHWRSDFFRUGLQJWRQHZUHVHDUFKIURPWKHDCLCFRUSRUDWLRQEULWDLQVWRSEXVLQHVVOHDGHUVDUHODUJHOBXQKHDUGXQUHFRJQLVHGDQGFRQVLGHUHGXQDEOHWRFRPPXQLFDWHHIIHFWLYHOBEBWKHLUEXVLQHVVSHHUVWKHUHVHDUFKUHYHDOHGWKDWZKLOHRIXNFRPSDQBGLUHFWRUVFRQVLGHUXVEXVLQHVVHAHFXWLYHVWRKDYHDQHAFHOOHQWRUJRRGPHGLDLPDJHDQGUHSXWDWLRQRQOBEHOLHYHWKHVDPHRIXNHAHFXWLYHVLQDGGLWLRQIHHOWKDWWKHPHGLDLPDJHRIWKHXNVOHDGLQJEXVLQHVVHAHFXWLYHVLVLQQHHGRILPSURYHPHQWWUDLQLQJCRQHOHDUQLQJZLUHLVVXHMXOBWRWRSRISDJHWRLQGHAWKHKXPEOHOHDGHUDQDUWLFOHLQEXOOHWSRLQWMXQHLVVXHDUJXHVWKDWKDYLQJDODUJHUWKDQOLIHFRUSRUDWHKHURDVDOHDGHUFDQEHGHWULPHQWDOWRDQRUJDQLVDWLRQWKHPDLQFULWLFLVPVRIWKLVWBSHRIOHDGHUDUHWKDWWKHBDUHVHOIVHUYLQJPRUHLQWHUHVWHGLQVHOISURPRWLRQDQGFHOHEULWBWKDQWHDPZRUNWKHDUWLFOHIXUWKHUVXJJHVWVWKDWLQPDQBFDVHVWKHBIDLOWRDGGYDOXHGRQRWGHOLYHUVXVWDLQDEOHUHVXOWVDQGGRQWZRUNWRLPSURYHSHUIRUPDQFHWKHDUWLFOHWHOOVXVWKDWWUXOBWUDQVIRUPDWLRQDOOHDGHUVKDYHDQHTXDOUDWLRRIKXPLOLWBDQGSURIHVVLRQDOZLOOWKHBDUHDEOHPDQDJHUVUDWKHUWKDQDIJXUHKHDGIRUWKHPHGLDDQGFDQHQJHQGHUHPSORBHHWUXVWFRPPLWPHQWDQGORBDOWBWKHBZLOODOVRKDYHDGHVLUHWRVKXQSXEOLFLWBFKDQQHODPEWLRQLQWRGHYHORSLQJWKHFRPSDQBQRWWKHPVHOYHVJLYHFUHGLWWRRWKHUVDURXQGWKHPDQGGHVSLVHPHGLRFULWBWRWRSRISDJHWRLQGHAZKDWDPHVVSDUWLFSDWLRQDVDVPSOHPDQDJHULDOUXOHWRFRPSOHALIBRUJDQLVDWLRQVDFWXDOOBDVHULRXVUHVHDUFKSDSHUZKLFKORRNVDWVRPHRIWKHVLPSOHUXOHVRIPDQDJHPHQWZKFKQWKHHQGFDQIRXOXSRXUOLYHVIRUJRRGEXWRQOBLIZHOHWWKHPZHDOOLDVVXPHNQRZRIWKHKRUVHPDGHEBDFRPPLWWHHLQWRGDBVFRQVXOWDWLYHFOPDWHZHFRXOGEHKHDGLQJIRUWUBLQJWRGHDOLQFDPHOVXQOHVVXOWLPDWHOBWKHPDQDJHULHWKHVLQJOHSHUVRQUHVSRQVLEOHIRUPDNLQJDQGLPSOHPHQWQJWKHGHFLVLRQGHFLGHVRXUKRUVHVVKRXOGQRWKDYHKXPSVZKHWKHURQHRUWZRLVLPPDWHULDOVRLQWKHHQGZHKDYHWKHDXWRFUDWLFGLFWDWRULDOYLFWRULDQSDUHQWZKRVHRIIVSULQJPLJKWLIGDULQJWRTXHVWLRQUHFHLYHWKHUHVSRQVHEHFDXVHLVDBLWLVMRXUQDORIPDQDJHPHQWVWXGLHVPDUFKXSGDWHFRPPHQWRQWKHRWKHUKDQGWKHHXURSHDQGLUHFWLYHVDBVWKRXVKDOWFRQVXOWDQGDWOHQJWKXQOHVVWKHUHDUHOHVVWKDQVWDIILQBRXURUJDQLVDWLRQVRUUBJXBVWKDWPHDQVWKDWLFDQFRQWLQXHWREHWKHDXWRFUDWFGFWDWRULDOSDUHQWWBSHDWOHDVWLQODZLIQRWUHDOLWBWRWRSRISDJHWRLQGHAOHDGHUVQHHGPRUHWUDLQLQJDBHDUDIWHUWKHOLEUDUBZRUOGVUHFUXWUHWDQDQGOHDGUHSRUWZDUQHGRIIDOOLQJVWDQGDUGVLQHAHFXWLYHDELOLWBPXVHXPVDUHIDFLQJDVLPODUOHDGHUVKLSFULVLVVSHDNLQJDWWKHDQQXDOPXVHXPGUHFWRUVFRQIHUHQFHOLCDPRVRIWKHFRXQFLOIRUHAFHOOHQFHLQPDQDJHPHQWDQGOHDGHUVKLSWROGGHOHJDWHVWKDWWKHBVKRXOGKHHGWKHGVTXHWEHLQJYRLFHGEBMXQLRUDQGPLGGOHPDQDJHUVLQWKHSXEOLFVHFWRUDFFRUGQJWRDUHFHQWUHSRUWRIMXQLRUDQGPLGGOHPDQDJHUVFODLPWKDWOHDGHUVKSQWKHLURUJDQLVDWLRQLVSRRUPVDPRVEHOLHYHVWKDWWKLVPDWWHUVEHFDXVHJRRGOHDGHUVFDQQVSLUHDQGHQHUJLVHWKHLUHPSORBHHVZKLFKKDVDSRVWYHHIIHFWRQSHUIRUPDQFHOLEUDUBDQGLQIRUPDWLRQXSGDWHMXOBYROWRWRSRISDJHWRLQGHASDWKWRWKHJDWHZDBLVFOHDUHGDBHDUDJRDQHQWUHSUHQHXUVHHNLQJKHOSWRVHWXSDFRPSDQBLQJODVJRZULVNHGEHLQJNQRFNHGGRZQLQDUXVKRIDJHQFLHVEUDQGLVKLQJPRUHWKDQGLIIHUHQWVXSSRUWSURGXFWVDQGVHUYLFHVQHZEXVLQHVVHVIDFHGDEHZLOGHULQJFKRLFHRIGLIIHUHQWSXEOLFVHFWRUDJHQFLHVSURYLGLQJDFFHVVWRRYHUEXVLQHVVVXSSRUWSDUWQHUVKSVPRVWOBNQRZQEBFRQIXVLQJWKUHHOHWWHUDFURQBPVBHWGHVSLWHWKHZHOWHURIVHUYLFHVDYDLODEOHZLWKOLWHUDOOBKXQGUHGVRIDGYLVHUVJUDQWVDQGWUDLQLQJVFKHPHVRQRIIHUUHVHDUFKVKRZHGWKDWJODVJRZXUJHQWOBQHHGHGWRILQGEHWWHUZDBVWRLPSURYHLWVEXVLQHVVELUWKUDWHDQGLWVLQGLJHQRXVFRPSDQBVXUYLYDOUDWHWKHYXOQHUDELOLWBRIVPDOODQGPHGLXPVLCHGHQWHUSULVHVVPHVWRIDLOXUHQWKHLUHDUOBBHDUVLVFOHDUDQGLQJODVJRZRQOBRIVPHVVXUYLYHORQJHUWKDQWKUHHBHDUVFRPSDUHGWRWKHQDWLRQDOWKUHHBHDUVXUYLYDOUDWHRIRQWRSRIORZHUWKDQDYHUDJHVXUYLYDOUDWHVJODVJRZDOVRKDGDSUREOHPZLWKHXURSHDQEXVLQHVVJUDQWVEHLQJOHIWXQFODLPHGEHFDXVHHOLJLEOHFRPSDQHVGGQRWDSSOBIRUWKHFDVKRQRIIHUGXQFDQWDQQDKLOOFKLHIHAHFXWLYHRIJODVJRZFKDPEHURIFRPPHUFHVHCHGWKHFKDQFHWRSRROWKHUHVRXUFHVRIWKHSULYDWHDQGSXEOFVHFWRUVLQDPDMRUHIIRUWWRDGGUHVVWKHVKRUWFRPLQJVRIWKHVBVWHPDQGFUHDWHDVQJOHSRLQWRIHQWUBIRUFRPSDQLHVVHHNQJKHOSDWDQBVWDJHRIWKHLUGHYHORSPHQWVPDOOEXVLQHVVJDWHZDBLVDWYDOHULHGDUURFKVFRWWLVKKHUDOGMXOBPBVFKRROGDBVZHUHWKHKDSSHVWGDBVRIPB".ToUpper();
string largeKey = "defghijklmnopqrstuvwxyzabc";
```
### 1. Encrypt Algorithm
```csharp
public string Encrypt(string plainText, string key)
{
    String cipherText = "";

    char[] alphabet = { 'a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z' };
    Dictionary<char, char> encrypt = new Dictionary<char, char>();
    for (int i = 0; i < alphabet.Length; i++)
    {
        encrypt.Add(alphabet[i], key[i]);
    }
    for (int i = 0; i < plainText.Length; i++)
    {
        cipherText += encrypt[Char.ToLower(plainText[i])];
    }
    return cipherText;
}
```
### 2. Decryption Algorithm
```csharp
public string Decrypt(string cipherText, string key)
{
    String decipher = "";
    char[] alphabet = { 'a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z' };
    Dictionary<char, char> decrypt = new Dictionary<char, char>();
    for (int i = 0; i < alphabet.Length; i++)
    {
        decrypt.Add(key[i], alphabet[i]);
    }
    for (int i = 0; i < cipherText.Length; i++)
    {
        decipher += decrypt[Char.ToLower(cipherText[i])];
    }
    return decipher;
}
```
### 4. Naive Analysis
```csharp
public string Analyse(string plainText, string cipherText)
{
    string alphabit  = "abcdefghijklmnopqrstuvwxyz";
    string alphabit1 = "abcdefghijklmnopqrstuvwxyz";
    char[] key = new char[alphabit.Length];
    cipherText = cipherText.ToLower();
    for (int i = 0; i < plainText.Length; i++)

    {
        int j = alphabit.IndexOf(plainText[i]);

        if (j!=-1)
        {
            key[j] = cipherText[i];
            alphabit1 = alphabit1.Replace(cipherText[i].ToString(),"");
        }
    }
    string new1key = string.Join("", key);
    Console.WriteLine(new1key+"  "+alphabit1);
    for (int x = 0; x < key.Length; x++)
    {
        if (key[x] == '\0')
        {
            key[x] = alphabit1[0];
            alphabit1 = alphabit1.Remove(0,1);
        }
    }
    string newkey = string.Join("", key);
    Console.WriteLine(newkey);
    return newkey;
}
```
### 4. Frequency Analysis
```csharp
/// Frequency Information:
/// E   12.51%
/// T	9.25
/// A	8.08
/// O	7.60
/// I	7.26
/// N	7.09
/// S	6.54
/// R	6.12
/// H	5.49
/// L	4.14
/// D	3.99
/// C	3.06
/// U	2.71
/// M	2.53
/// F	2.30
/// P	2.00
/// G	1.96
/// W	1.92
/// Y	1.73
/// B	1.54
/// V	0.99
/// K	0.67
/// X	0.19
/// J	0.16
/// Q	0.11
/// Z	0.09

public string AnalyseUsingCharFrequency(string cipher)
{
    List<KeyValuePair<char, int>> cipherFreq = new List<KeyValuePair<char, int>>();
    Dictionary<char, char> keyMap = new Dictionary<char, char>();

    char[] freqInfo = {
    'E', 'T', 'A', 'O', 'I', 'N', 'S', 'R', 'H', 'L', 'D', 'C', 'U',
    'M', 'F', 'P', 'G', 'W', 'Y', 'B', 'V', 'K', 'X', 'J', 'Q', 'Z'};

    int[] freqChar = new int[26];

    for (int i = 0; i < cipher.Length; i++)
    {
        freqChar[cipher[i] - 'A']++;
    }


    char key;
    for (int i = 0; i < 26; i++)
    {
        key = (char)(i + 'A');
        cipherFreq.Add(new KeyValuePair<char, int>(key, freqChar[i]));
    }
    cipherFreq = cipherFreq.OrderByDescending(pair => pair.Value).ToList();

    for (int i = 0; i < cipherFreq.Count; i++)
    {
        keyMap.Add(cipherFreq[i].Key, freqInfo[i]);
    }

    string finalRes = "";
    for (int i = 0; i < cipher.Length; i++)
    {
        finalRes += keyMap[cipher[i]];
    }

    return finalRes.ToLower();
}
```
