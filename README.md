local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then v19=v0(v3(v30,1,1));return "";else local v91=v2(v0(v30,16));if v19 then local v113=v5(v91,v19);v19=nil;return v113;else return v91;end end end);local function v20(v31,v32,v33) if v33 then local v92=0 -0 ;local v93;while true do if (v92==(0 -0)) then v93=(v31/((879 -(282 + 132 + 463))^(v32-(1638 -(1523 + 114)))))%((2 + 0)^(((v33-(1 -0)) -(v32-(1 -(957 -(892 + 65))))) + (2 -1))) ;return v93-(v93%(620 -(555 + 64))) ;end end else local v94=(933 -((2043 -1186) + 74))^(v32-(569 -(367 + 201))) ;return (((v31%(v94 + v94))>=v94) and 1) or ((1712 -785) -(214 + 699 + 14)) ;end end local function v21() local v34=0 -0 ;local v35;while true do if (v34==(351 -(87 + 194 + 69))) then return v35;end if (v34==(180 -((266 -199) + 113))) then v35=v1(v16,v18,v18);v18=v18 + 1 + 0 ;v34=2 -1 ;end end end local function v22() local v36=952 -(802 + 150) ;local v37;local v38;while true do if (v36==1) then return (v38 * (689 -433)) + v37 ;end if (v36==(0 -(0 -0))) then v37,v38=v1(v16,v18,v18 + 2 + 0 );v18=v18 + (999 -(915 + 82)) ;v36=1;end end end local function v23() local v39,v40,v41,v42=v1(v16,v18,v18 + (3 -1) + 1 );v18=v18 + (4 -0) ;return (v42 * (16778403 -(1069 + 118))) + (v41 * 65536) + (v40 * ((101 + 479) -324)) + v39 ;end local function v24() local v43=0;local v44;local v45;local v46;local v47;local v48;local v49;while true do if (v43==3) then if (v48==0) then if (v47==(0 -0)) then return v49 * ((885 -(261 + 624)) + 0) ;else v48=(1407 -615) -(368 + 423) ;v46=(1080 -(1020 + 60)) -(1423 -(630 + 793)) ;end elseif (v48==(2065 -(10 + 8))) then return ((v47==(0 -0)) and (v49 * ((443 -(416 + (87 -61)))/(0 -0)))) or (v49 * NaN) ;end return v8(v49,v48-1023 ) * (v46 + (v47/((1 + 1)^(91 -39)))) ;end if (v43==((2083 -1643) -(145 + 293))) then v48=v20(v45,(178 + 273) -(44 + 386) ,1517 -(998 + 488) );v49=((v20(v45,11 + 21 )==(1 + 0)) and  -(773 -(201 + 571))) or 1 ;v43=(3928 -2787) -(116 + (2769 -(760 + 987))) ;end if (v43==(4 -3)) then v46=1 + 0 ;v47=(v20(v45,3 -(1915 -(1789 + 124)) ,71 -51 ) * ((861 -(814 + 45))^(78 -46))) + v44 ;v43=2;end if (v43==(0 + 0)) then v44=v23();v45=v23();v43=1 + (766 -(745 + 21)) ;end end end local function v25(v50) local v51;if  not v50 then v50=v23();if (v50==(0 + 0)) then return "";end end v51=v3(v16,v18,(v18 + v50) -(2 -1) );v18=v18 + v50 ;local v52={};for v68=1, #v51 do v52[v68]=v2(v1(v3(v51,v68,v68)));end return v6(v52);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v53=(function() return function(v95,v96,v97,v98,v99,v100,v101,v102,v103) local v104=(function() return 0;end)();local v95=(function() return;end)();local v96=(function() return;end)();while true do local v112=(function() return 0;end)();while true do if (v112==(0 + 0)) then if ((1 + 0)==v104) then while true do if (v95==0) then v96=(function() return v97();end)();if (v98(v96, #"]", #"}")~=(0 -0)) then else local v125=(function() return 0;end)();local v126=(function() return;end)();local v127=(function() return;end)();local v128=(function() return;end)();local v129=(function() return;end)();while true do if (v125==1) then local v131=(function() return 0 -0 ;end)();while true do if (1==v131) then v125=(function() return 1386 -(746 + 638) ;end)();break;end if (v131==0) then v128=(function() return nil;end)();v129=(function() return nil;end)();v131=(function() return 1;end)();end end end if (v125~=(1 + 1)) then else while true do if (v126==2) then local v256=(function() return 0 -0 ;end)();local v257=(function() return;end)();while true do if (v256==(341 -(218 + 123))) then v257=(function() return 0;end)();while true do if (v257~=(1582 -(1535 + 46))) then else v126=(function() return  #"nil";end)();break;end if (v257~=(0 + 0)) then else if (v98(v128, #"/", #"[")~= #"<") then else v129[2]=(function() return v99[v129[2]];end)();end if (v98(v128,1 + 1 ,562 -(306 + 254) )== #"|") then v129[ #"xxx"]=(function() return v99[v129[ #"gha"]];end)();end v257=(function() return 1 + 0 ;end)();end end break;end end end if ( #"xnx"==v126) then if (v98(v128, #"nil", #"19(")== #"[") then v129[ #"0836"]=(function() return v99[v129[ #"0836"]];end)();end v100[v101]=(function() return v129;end)();break;end if (v126== #",") then local v259=(function() return 0 -0 ;end)();local v260=(function() return;end)();while true do if (0==v259) then v260=(function() return 0;end)();while true do if (v260==(1467 -(899 + 568))) then v129=(function() return {v102(),v102(),nil,nil};end)();if (v127==0) then local v385=(function() return 0 + 0 ;end)();local v386=(function() return;end)();while true do if (v385==(0 -0)) then v386=(function() return 0;end)();while true do if (0==v386) then v129[ #"asd"]=(function() return v102();end)();v129[ #"?id="]=(function() return v102();end)();break;end end break;end end elseif (v127== #":") then v129[ #"91("]=(function() return v103();end)();elseif (v127==2) then v129[ #"asd"]=(function() return v103() -(2^(619 -(268 + 335))) ;end)();elseif (v127== #"19(") then local v393=(function() return 0;end)();local v394=(function() return;end)();while true do if (v393~=(290 -(60 + 230))) then else v394=(function() return 572 -(426 + 146) ;end)();while true do if (v394~=(0 + 0)) then else v129[ #"asd"]=(function() return v103() -(2^(1472 -(282 + 1174))) ;end)();v129[ #".dev"]=(function() return v102();end)();break;end end break;end end end v260=(function() return 812 -(569 + 242) ;end)();end if (v260==1) then v126=(function() return 2;end)();break;end end break;end end end if (v126==(0 -0)) then local v261=(function() return 0 + 0 ;end)();local v262=(function() return;end)();while true do if (0==v261) then v262=(function() return 0;end)();while true do if ((1024 -(706 + 318))==v262) then v127=(function() return v98(v96,2, #"19(");end)();v128=(function() return v98(v96, #"http",1257 -(721 + 530) );end)();v262=(function() return 1272 -(945 + 326) ;end)();end if (v262~=(2 -1)) then else v126=(function() return  #"}";end)();break;end end break;end end end end break;end if (v125~=0) then else local v132=(function() return 0;end)();local v133=(function() return;end)();while true do if ((0 + 0)==v132) then v133=(function() return 700 -(271 + 429) ;end)();while true do if (v133==0) then v126=(function() return 0 + 0 ;end)();v127=(function() return nil;end)();v133=(function() return 1501 -(1408 + 92) ;end)();end if (v133==(1087 -(461 + 625))) then v125=(function() return 1289 -(993 + 295) ;end)();break;end end break;end end end end end break;end end return v95,v96,v97,v98,v99,v100,v101,v102,v103;end if (0~=v104) then else local v122=(function() return 0 + 0 ;end)();while true do if (v122==0) then v95=(function() return 0;end)();v96=(function() return nil;end)();v122=(function() return 1172 -(418 + 753) ;end)();end if (v122~=(1 + 0)) then else v104=(function() return 1 + 0 ;end)();break;end end end break;end end end end;end)();local v54=(function() return function(v105,v106,v107) local v108=(function() return 0;end)();local v109=(function() return;end)();while true do if (v108==(0 + 0)) then v109=(function() return 0;end)();while true do if (v109==(0 + 0)) then local v123=(function() return 529 -(406 + 123) ;end)();while true do if (v123==(1769 -(1749 + 20))) then local v124=(function() return 0 + 0 ;end)();while true do if ((1322 -(1249 + 73))~=v124) then else v105[v106-#"|" ]=(function() return v107();end)();return v105,v106,v107;end end end end end end break;end end end;end)();local v55=(function() return {};end)();local v56=(function() return {};end)();local v57=(function() return {};end)();local v58=(function() return {v55,v56,nil,v57};end)();local v59=(function() return v23();end)();local v60=(function() return {};end)();for v70= #"[",v59 do local v71=(function() return 1145 -(466 + 679) ;end)();local v72=(function() return;end)();local v73=(function() return;end)();local v74=(function() return;end)();while true do if (v71==1) then v74=(function() return nil;end)();while true do if (v72==(0 -0)) then v73=(function() return v21();end)();v74=(function() return nil;end)();v72=(function() return 2 -1 ;end)();end if (v72==(1901 -(106 + 1794))) then if (v73== #"[") then v74=(function() return v21()~=(0 + 0) ;end)();elseif (v73==2) then v74=(function() return v24();end)();elseif (v73~= #"19(") then else v74=(function() return v25();end)();end v60[v70]=(function() return v74;end)();break;end end break;end if ((0 + 0)~=v71) then else local v114=(function() return 0;end)();while true do if (v114~=(2 -1)) then else v71=(function() return 1;end)();break;end if (v114~=(0 -0)) then else v72=(function() return 0;end)();v73=(function() return nil;end)();v114=(function() return 115 -(4 + 110) ;end)();end end end end end v58[ #"nil"]=(function() return v21();end)();for v75= #"}",v23() do FlatIdent_8199B,Descriptor,v21,v20,v60,v55,v75,v22,v23=(function() return v53(FlatIdent_8199B,Descriptor,v21,v20,v60,v55,v75,v22,v23);end)();end for v76= #">",v23() do v56,v76,v28=(function() return v54(v56,v76,v28);end)();end return v58;end local function v29(v62,v63,v64) local v65=v62[585 -(57 + 527) ];local v66=v62[1429 -(41 + 1386) ];local v67=v62[(103 + 3) -(15 + 2 + 86) ];return function(...) local v77=v65;local v78=v66;local v79=v67;local v80=v27;local v81=1 + 0 ;local v82= -(1 -0);local v83={};local v84={...};local v85=v12("#",...) -(2 -1) ;local v86={};local v87={};for v110=166 -(45 + 77 + 44) ,v85 do if ((v110>=v79) or (3026<=2280)) then v83[v110-v79 ]=v84[v110 + (1 -0) ];else v87[v110]=v84[v110 + (3 -2) ];end end local v88=(v85-v79) + 1 + 0 ;local v89;local v90;while true do local v111=0 + 0 ;while true do if (v111==(1 + 0)) then if (v90<=(72 -36)) then if ((v90<=(82 -(6 + 24 + (64 -29)))) or (1653<=1108)) then if (v90<=(6 + (1913 -(340 + 1571)))) then if ((2909>2609) and (v90<=(1260 -(1043 + 214)))) then if ((757>194) and (v90<=(3 -2))) then if (v90==(1212 -(323 + 889))) then v87[v89[5 -3 ]]=v64[v89[2 + 1 ]];else v87[v89[(2354 -(1733 + 39)) -((991 -630) + (1253 -(125 + 909))) ]]=v87[v89[323 -(53 + 267) ]]%v89[1 + 3 ] ;end elseif (v90>(415 -((1963 -(1096 + 852)) + 398))) then v87[v89[984 -(18 + 964) ]][v87[v89[11 -8 ]]]=v87[v89[3 + 1 ]];else v87[v89[2]][v89[2 + 1 ]]=v87[v89[854 -(20 + 830) ]];end elseif (v90<=(4 + 1)) then if ((v90==(130 -(116 + 10))) or (31>=1398)) then v87[v89[1 + 1 ]]=v89[3] + v87[v89[742 -(542 + 196) ]] ;else v87[v89[3 -1 ]]=v29(v78[v89[1 + 2 ]],nil,v64);end elseif (v90<=(4 + 1 + 1)) then v87[v89[2]]={};elseif ((3196<=4872) and (v90==(3 + 4))) then local v263=v89[4 -2 ];local v264=v87[v263];for v308=v263 + ((2 -0) -1) ,v89[1554 -(1126 + 425) ] do v7(v264,v87[v308]);end else v81=v89[408 -(118 + 287) ];end elseif (v90<=(46 -34)) then if (v90<=(1131 -(118 + 1003))) then if ((3326==3326) and (v90==((26 + 0) -17))) then v87[v89[379 -(142 + 235) ]]=v87[v89[3]]%v87[v89[18 -14 ]] ;else for v229=v89[1 + (513 -(409 + 103)) ],v89[980 -(553 + 424) ] do v87[v229]=nil;end end elseif ((1433<=3878) and (v90>(20 -9))) then local v145=v89[2];do return v87[v145](v13(v87,v145 + 1 ,v89[3 + 0 ]));end else local v146=v89[2 + 0 ];local v147=v87[v146];local v148=v89[2 + 1 ];for v231=(237 -(46 + 190)) + 0 ,v148 do v147[v231]=v87[v146 + v231 ];end end elseif (v90<=(8 + (101 -(51 + 44)))) then if ((v90==((8 + 19) -(1331 -(1114 + 203)))) or (1583==1735)) then v87[v89[5 -3 ]]=v64[v89[6 -3 ]];else local v151=v89[1 + 1 ];v87[v151](v13(v87,v151 + (4 -3) ,v82));end elseif (v90<=(768 -((965 -(228 + 498)) + 514))) then local v152=0 + 0 + 0 ;local v153;while true do if ((v152==(1329 -(797 + 532))) or (2981==2350)) then v153=v89[2 + 0 ];v87[v153]=v87[v153](v13(v87,v153 + 1 ,v82));break;end end elseif (v90==(6 + 10)) then if  not v87[v89[(3 + 1) -2 ]] then v81=v81 + 1 ;else v81=v89[1205 -(373 + 829) ];end else local v266=v78[v89[734 -((1139 -(174 + 489)) + 255) ]];local v267;local v268={};v267=v10({},{__index=function(v311,v312) local v313=v268[v312];return v313[1131 -(369 + 761) ][v313[2]];end,__newindex=function(v314,v315,v316) local v317=0 + 0 ;local v318;while true do if ((v317==(0 -0)) or (4466<=493)) then v318=v268[v315];v318[1 -0 ][v318[240 -(64 + 174) ]]=v316;break;end end end});for v319=1 + 0 ,v89[1909 -(830 + 1075) ] do local v320=0 -0 ;local v321;while true do if ((v320==(337 -(144 + 192))) or (2547<=1987)) then if (v321[217 -(42 + 174) ]==(30 + 9)) then v268[v319-(1 + (524 -(303 + 221))) ]={v87,v321[1507 -(363 + 1141) ]};else v268[v319-(1581 -(1183 + 397)) ]={v63,v321[8 -5 ]};end v86[ #v86 + 1 ]=v268;break;end if (v320==(0 + 0)) then v81=v81 + 1 ;v321=v77[v81];v320=1 + 0 ;end end end v87[v89[1977 -(1913 + 62) ]]=v29(v266,v267,v64);end elseif (v90<=26) then if ((2961>2740) and (v90<=21)) then if ((3696>=3612) and (v90<=(12 + (1169 -(171 + 991))))) then if ((v90>(47 -29)) or (2970==1878)) then do return;end else local v154=v89[1935 -((2328 -1763) + 1368) ];local v155,v156=v80(v87[v154](v13(v87,v154 + 1 ,v82)));v82=(v156 + v154) -(3 -2) ;local v157=(4460 -2799) -(1477 + 184) ;for v234=v154,v82 do v157=v157 + (1 -0) ;v87[v234]=v155[v157];end end elseif ((v90==(19 + 1)) or (3693<1977)) then local v158=v89[858 -(564 + 292) ];local v159=v87[v158];local v160=v89[4 -1 ];for v237=2 -(2 -1) ,v160 do v159[v237]=v87[v158 + v237 ];end else v87[v89[306 -(244 + 49 + 11) ]][v89[3 + 0 ]]=v87[v89[480 -((143 -102) + 435) ]];end elseif (v90<=(1024 -(938 + 63))) then if (v90==(17 + 5)) then v87[v89[2]]={};else local v164=1125 -(936 + 189) ;local v165;local v166;local v167;while true do if (v164==1) then v167=v87[v165 + 1 + 1 ];if (v167>0) then if (v166>v87[v165 + (2 -1) ]) then v81=v89[3];else v87[v165 + (1616 -((2522 -957) + 48)) ]=v166;end elseif ((v166<v87[v165 + 1 + 0 ]) or (930>2101)) then v81=v89[1141 -(782 + (1100 -744)) ];else v87[v165 + (270 -(176 + (1339 -(111 + 1137)))) ]=v166;end break;end if (v164==0) then v165=v89[4 -2 ];v166=v87[v165];v164=1 -0 ;end end end elseif ((4153>3086) and (v90<=((1274 -(91 + 67)) -(975 + 117)))) then v87[v89[1877 -(157 + 1718) ]][v87[v89[3 + 0 ]]]=v87[v89[14 -10 ]];elseif (v90>(85 -60)) then if (v87[v89[1020 -((2074 -1377) + 321) ]]==v89[10 -(2 + 4) ]) then v81=v81 + (1 -0) ;else v81=v89[(529 -(423 + 100)) -3 ];end else v87[v89[1 + 1 ]][v87[v89[2 + 1 ]]]=v89[6 -2 ];end elseif (v90<=31) then if ((v90<=(74 -(126 -80))) or (4654<=4050)) then if (v90>(1254 -(322 + 905))) then local v170=0;local v171;while true do if (v170==(611 -(602 + 9))) then v171=v89[1191 -(449 + 740) ];v87[v171]=v87[v171](v13(v87,v171 + (873 -(826 + 46)) ,v89[(496 + 454) -((1016 -(326 + 445)) + 702) ]));break;end end else v87[v89[2]][v87[v89[9 -6 ]]]=v89[2 + 2 ];end elseif (v90<=((8409 -6482) -((579 -319) + 1638))) then for v240=v89[442 -(382 + 58) ],v89[3] do v87[v240]=nil;end elseif ((v90==(96 -66)) or (2602<1496)) then local v272=v89[2 + 0 ];local v273=v87[v89[5 -2 ]];v87[v272 + ((4 -2) -1) ]=v273;v87[v272]=v273[v89[1209 -(902 + 303) ]];else do return;end end elseif (v90<=33) then if (v90==(69 -37)) then v87[v89[4 -2 ]]=v63[v89[3]];else v81=v89[1 + 2 ];end elseif (v90<=34) then local v177=1690 -(1121 + 569) ;local v178;local v179;local v180;local v181;while true do if (v177==(214 -(22 + 192))) then v178=v89[685 -(483 + 200) ];v179,v180=v80(v87[v178](v87[v178 + (1464 -(1404 + 59)) ]));v177=2 -1 ;end if (v177==1) then v82=(v180 + v178) -1 ;v181=0 -0 ;v177=713 -(530 + 181) ;end if ((v177==2) or (1020>2288)) then for v347=v178,v82 do v181=v181 + (766 -(468 + 297)) ;v87[v347]=v179[v181];end break;end end elseif (v90>(597 -(334 + 228))) then v87[v89[6 -4 ]]=v87[v89[3]]%v89[8 -4 ] ;else v87[v89[(883 -(614 + 267)) -0 ]]=v87[v89[1 + 2 ]];end elseif (v90<=55) then if ((328==328) and (v90<=(281 -(141 + 95)))) then if (v90<=40) then if ((1511<3808) and (v90<=((70 -(19 + 13)) + 0))) then if ((v90==((152 -58) -57)) or (2510>4919)) then v87[v89[(9 -5) -2 ]]= #v87[v89[1 + 2 ]];else local v183=v89[2];local v184=v87[v183];local v185=v87[v183 + (5 -3) ];if (v185>0) then if (v184>v87[v183 + (2 -1) ]) then v81=v89[3];else v87[v183 + 1 + 2 + 0 ]=v184;end elseif (v184<v87[v183 + 1 ]) then v81=v89[3];else v87[v183 + 2 + 1 ]=v184;end end elseif ((4763==4763) and (v90==(54 -15))) then v87[v89[2 + 0 ]]=v87[v89[166 -(92 + 71) ]];else v87[v89[1 + 1 ]]=v89[4 -1 ];end elseif ((4137>1848) and (v90<=(807 -(574 + 191)))) then if (v90>(34 + 7)) then local v190=v89[4 -2 ];do return v13(v87,v190,v82);end else local v191=v89[2 + 0 ];local v192,v193=v80(v87[v191](v13(v87,v191 + (1 -0) ,v89[(1766 -914) -(254 + 595) ])));v82=(v193 + v191) -(127 -(55 + 71)) ;local v194=0 -0 ;for v242=v191,v82 do v194=v194 + (1791 -((2385 -(1293 + 519)) + 1217)) ;v87[v242]=v192[v194];end end elseif ((2436<=3134) and (v90<=(119 -76))) then local v195=v89[1 + 1 ];do return v13(v87,v195,v82);end elseif ((3723==3723) and (v90==(70 -26))) then local v280=939 -(714 + 225) ;local v281;local v282;local v283;local v284;while true do if (v280==(2 -(1 -0))) then v82=(v283 + v281) -((2 -1) -(0 -0)) ;v284=0 + 0 ;v280=2 -0 ;end if ((v280==2) or (4046>=4316)) then for v365=v281,v82 do v284=v284 + (807 -(118 + (2966 -2278))) ;v87[v365]=v282[v284];end break;end if ((v280==0) or (2008<1929)) then v281=v89[50 -(25 + 23) ];v282,v283=v80(v87[v281](v87[v281 + 1 ]));v280=1 + 0 ;end end else v87[v89[1888 -(927 + 959) ]]= #v87[v89[3]];end elseif ((2384>1775) and (v90<=(168 -118))) then if (v90<=(779 -(16 + 716))) then if (v90>(88 -42)) then local v196=v89[2];local v197=v87[v89[100 -(11 + (202 -116)) ]];v87[v196 + (2 -1) ]=v197;v87[v196]=v197[v89[4]];else local v201=(151 + 134) -(175 + 110) ;local v202;while true do if (((0 -0)==v201) or (4543<=4376)) then v202=v89[2];v87[v202](v13(v87,v202 + (4 -3) ,v89[1 + 2 ]));break;end end end elseif ((728==728) and (v90<=(1844 -((1168 -665) + 1293)))) then v87[v89[5 -(1 + 2) ]]();elseif ((v90==49) or (1076>4671)) then local v286=v89[2];v87[v286](v87[v286 + 1 ]);else local v287=v89[2 + 0 ];local v288,v289=v80(v87[v287](v13(v87,v287 + (1062 -(810 + 251)) ,v82)));v82=(v289 + v287) -1 ;local v290=0 + 0 ;for v329=v287,v82 do v290=v290 + 1 + 0 ;v87[v329]=v288[v290];end end elseif (v90<=(47 + 5)) then if (v90==51) then local v203=v89[535 -(43 + 490) ];v87[v203]=v87[v203]();else local v205=v89[735 -(711 + 22) ];v87[v205](v13(v87,v205 + (3 -2) ,v89[862 -(80 + 160 + 619) ]));end elseif ((1851>=378) and (v90<=(13 + 40))) then v87[v89[2 -0 ]]=v29(v78[v89[3]],nil,v64);elseif (v90>(34 + 20)) then local v291=v89[1 + (1097 -(709 + 387)) ];v87[v291]=v87[v291]();else local v293=1744 -((3202 -(673 + 1185)) + 400) ;local v294;while true do if (v293==(405 -(255 + (435 -285)))) then v294=v89[2];v87[v294]=v87[v294](v13(v87,v294 + 1 + 0 ,v82));break;end end end elseif (v90<=64) then if ((v90<=(32 + 27)) or (1948>=3476)) then if (v90<=(243 -186)) then if (v90>(180 -124)) then local v207=1739 -(404 + 1335) ;local v208;local v209;local v210;while true do if ((4794>=833) and (((1303 -897) -(183 + 223))==v207)) then v208=v89[2 -0 ];v209=v87[v208 + 2 + 0 ];v207=1 + 0 ;end if (v207==(338 -(10 + 327))) then v210=v87[v208] + v209 ;v87[v208]=v210;v207=2;end if (v207==2) then if (v209>((0 -0) + 0)) then if (v210<=v87[v208 + (339 -(118 + 220)) ]) then v81=v89[1 + 0 + 2 ];v87[v208 + (452 -(108 + 341)) ]=v210;end elseif ((4090==4090) and (v210>=v87[v208 + 1 ])) then local v376=0;while true do if ((0 + 0)==v376) then v81=v89[12 -9 ];v87[v208 + 3 ]=v210;break;end end end break;end end else local v211=(1116 + 377) -(711 + 782) ;local v212;while true do if (v211==(0 -(0 -0))) then v212=v89[(116 + 355) -(270 + (396 -197)) ];v87[v212]=v87[v212](v13(v87,v212 + 1 + 0 ,v89[1822 -((1138 -558) + 1239) ]));break;end end end elseif ((v90==(172 -114)) or (3758==2498)) then local v213=v89[2 + 0 ];v87[v213](v87[v213 + 1 + 0 ]);else local v214=0 + 0 ;local v215;local v216;local v217;while true do if (v214==((1882 -(446 + 1434)) -1)) then v217=v87[v215] + v216 ;v87[v215]=v217;v214=2 + (1283 -(1040 + 243)) ;end if (v214==(1167 -(645 + 522))) then v215=v89[1792 -(1010 + 780) ];v216=v87[v215 + 2 ];v214=(2 -1) + 0 ;end if (v214==(9 -7)) then if (v216>(0 -0)) then if (v217<=v87[v215 + (1837 -(1045 + 791)) ]) then v81=v89[3];v87[v215 + ((1854 -(559 + 1288)) -4) ]=v217;end elseif ((v217>=v87[v215 + (1 -0) ]) or (2673<1575)) then v81=v89[508 -(351 + 154) ];v87[v215 + 3 ]=v217;end break;end end end elseif (v90<=(1635 -(1281 + 293))) then if ((v90>(326 -(28 + 238))) or (3721<=1455)) then if  not v87[v89[4 -2 ]] then v81=v81 + (1560 -(1381 + 178)) ;else v81=v89[3 + (1931 -(609 + 1322)) ];end else local v218=v78[v89[3 + 0 ]];local v219;local v220={};v219=v10({},{__index=function(v245,v246) local v247=v220[v246];return v247[1 + 0 ][v247[6 -4 ]];end,__newindex=function(v248,v249,v250) local v251=0 + 0 ;local v252;while true do if ((470 -(381 + 89))==v251) then v252=v220[v249];v252[1 + 0 ][v252[2 + 0 ]]=v250;break;end end end});for v253=1 -0 ,v89[4] do v81=v81 + (1157 -(1074 + (306 -224))) ;local v254=v77[v81];if ((934<2270) and (v254[1 -0 ]==(101 -62))) then v220[v253-(1785 -(214 + 1570)) ]={v87,v254[3]};else v220[v253-1 ]={v63,v254[3 + 0 ]};end v86[ #v86 + ((10 -7) -2) ]=v220;end v87[v89[1728 -(1668 + 58) ]]=v29(v218,v219,v64);end elseif ((v90<=(688 -(512 + 114))) or (1612==1255)) then v87[v89[5 -3 ]]=v87[v89[5 -2 ]]%v87[v89[4]] ;elseif (v90==(219 -(56 + 100))) then local v296=v89[1 + 1 ];local v297,v298=v80(v87[v296](v13(v87,v296 + 1 + 0 ,v89[3 + 0 ])));v82=(v298 + v296) -(3 -2) ;local v299=1994 -(48 + 61 + 1885) ;for v342=v296,v82 do local v343=1469 -((3765 -2496) + 200) ;while true do if (v343==(0 -0)) then v299=v299 + ((447 + 369) -(98 + 717)) ;v87[v342]=v297[v299];break;end end end else v87[v89[2]]=v87[v89[829 -(802 + 24) ]][v89[4]];end elseif (v90<=69) then if (v90<=(113 -47)) then if (v90>65) then v87[v89[2 -0 ]]=v87[v89[1 + 2 ]] + v89[4 + 0 ] ;else local v224=v89[1 + (1 -0) ];v87[v224](v13(v87,v224 + 1 ,v82));end elseif (v90<=(15 + 52)) then v87[v89[5 -3 ]]=v89[9 -6 ] + v87[v89[2 + 2 ]] ;elseif (v90>(28 + 40)) then v87[v89[2]]=v89[3 + 0 ];else v87[v89[2 + 0 + 0 ]]=v63[v89[2 + 1 ]];end elseif (v90<=(1504 -(797 + 636))) then if (v90==((189 + 150) -269)) then v87[v89[1621 -(1427 + 192) ]]=v87[v89[2 + 1 ]][v89[3 + 1 ]];else v87[v89[4 -2 ]]();end elseif ((v90<=(65 + 7)) or (4352<4206)) then v87[v89[1 + 1 ]]=v87[v89[329 -(192 + 134) ]] + v89[1280 -(316 + 960) ] ;elseif (v90==(41 + 32)) then local v306=0 + 0 ;local v307;while true do if ((v306==0) or (2860<=181)) then v307=v89[2];do return v87[v307](v13(v87,v307 + 1 + 0 ,v89[11 -8 ]));end break;end end elseif (v87[v89[2]]==v89[(467 + 88) -(82 + 1 + 468) ]) then v81=v81 + ((2240 -(153 + 280)) -(1202 + 604)) ;else v81=v89[13 -10 ];end v81=v81 + 1 ;break;end if ((0 -0)==v111) then v89=v77[v81];v90=v89[2 -1 ];v111=326 -(45 + 280) ;end end end end;end return v29(v28(),{},v17)(...);end return v15("LOL!953Q0003063Q00737472696E6703043Q006368617203043Q00627974652Q033Q0073756203053Q0062697433322Q033Q0062697403043Q0062786F7203053Q007461626C6503063Q00636F6E63617403063Q00696E73657274025Q00804A4003083Q0079C9E95A58F3835103073Q00E03AA885363A92025Q0080494003043Q0076217EF903063Q00203840139C3A025Q0080484003153Q00D146754AF05D7518A55A711AF54B744ACA457113A403043Q006A852E10026Q00484003083Q009DF3CDCE38CFB17503083Q001EDE92A1A25AAED2025Q0080474003053Q00C9CEC824A703043Q005D86A5AD026Q00474003043Q008379B48503053Q0053CD18D9E0025Q0080464003063Q006ECB3BD3164203053Q006427AC55BC026Q00464003073Q008DAA054DB9E5DC03073Q00AFCCC97124D68B025Q0080454003053Q00A5085E41E103073Q0080EC653F268421026Q00454003083Q00F00A15D2A27589DA03073Q00E6B47F67B3D61C026Q00444003073Q00068BB15801860503083Q007045E4DF2C64E871025Q0080434003153Q009EDE02F968E2EDF41EFA7DF5B99D35F471FAA9D45103063Q0096CDBD709018026Q00434003053Q002EE4ACBCA903073Q00C77A8DD8D0CCDD026Q00424003043Q00AC2DC41C03053Q0087E14CAD72026Q003F402Q033Q003A35AB03073Q00497150D2582E57026Q003E40030F3Q00E41D83F5E1C616A4E5C5CE3C8BE3CF03053Q00AAA36FE297026Q003D4003073Q000B0F94C3813D1703053Q00CA586EE2A6026Q003C4003043Q00F9C3088103073Q006BB28651D2C69E026Q003B4003083Q009EE0D7C196E8D6C103043Q00A4D889BB026Q00394003043Q007651112C03073Q0072383E6549478D026Q00374003083Q00E7D1EC48DDD0E25903043Q003CB4A48E026Q003640030E3Q007D2D4678391ECB5F3B4B3D2857B803073Q009836483F58453E026Q00354003053Q0033E7B1C20203043Q00AE678EC5026Q003440030B3Q00E32B39B3B10DE8C120279303073Q009CA84E40E0D479026Q00334003093Q00EC516927A00DD3517D03063Q007EA7341074D9026Q003240030D3Q003513B42E0A14BC392D19B0251403043Q004B6776D9026Q003140030C3Q0085FF3B53EEAE9FF53E54F6AC03063Q00C7EB90523D98026Q00304003063Q009FE73CC20CAB03083Q00A7D6894AAB78CE53026Q002E4003073Q0029C05F702Q72F703083Q00876CAE3E121E1793026Q002C4003073Q009FD0515E11A9DD03053Q007EDBB9223D026Q002A40030B3Q000CD92D8539CD29C801D42E03043Q00E849A14C026Q00284003083Q00ED352BE3F0ABC63903063Q00CAAB5C4786BE026Q002640030A3Q0024B58733DC10948A3ADC03053Q00B962DAEB57026Q00244003073Q0099CDD6080E2EB803063Q004BDCA3B76A62026Q00224003133Q006A4D0E23404515374856092A47710133404C0703043Q0045292260026Q001C40030F3Q009759C8A4335E37F2AE54DDA92E5C3503083Q00A1DB36A9C05A3050026Q001440030C3Q0035B0D0DB8422332DB6C5D38803073Q005479DFB1BFED4C026Q00084003043Q00867C712D03083Q0023C81D1C4873149A028Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q7470476574031C3Q00682Q7470733A2Q2F7369726975732E6D656E752F7261796669656C64030C3Q0043726561746557696E646F77031B3Q00F09F2Q8C4D454E552050524F54454354494F4EF09F2Q8C20352E30031E3Q00F09F94A5204B47756573744368656174734A2053756E61722120F09F94A503243Q004B47756573744368656174734A205461726166C4B16E64616E20596170C4B16C64C4B121012Q002Q01030E3Q00C59E696672652053697374656D6903243Q00C59E696672657969204B47756573744368656174734A2A44656E20416CC4B16EC4B17A2103213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F725A35706D772Q41026Q00F03F03093Q00437265617465546162030F3Q004D656EC3BC204B6F72756D6173C4B1030D3Q0043726561746553656374696F6E027Q004003063Q004E6F74696679032A3Q00F09F94A54775657374436865617473205461726166C4B16E64616E20596170C4B16C64C4B121F09F2Q8C022Q0050ABA24D0842030C3Q0043726561746542752Q746F6E03213Q00F09F2Q8C4B47756573744368656174734A204875622041C3A720352E30F09FA9B8005B013Q00067Q00122Q000100013Q00204600010001000200122Q000200013Q00204600020002000300122Q000300013Q00204600030003000400122Q000400053Q00063D0004000B000100010004213Q000B000100122Q000400063Q00204600050004000700122Q000600083Q00204600060006000900122Q000700083Q00204600070007000A00061100083Q000100062Q00273Q00074Q00273Q00014Q00273Q00054Q00273Q00024Q00273Q00034Q00273Q00064Q0023000900083Q001228000A000C3Q001228000B000D4Q00380009000B00020010023Q000B00092Q0023000900083Q001228000A000F3Q001228000B00104Q00380009000B00020010023Q000E00092Q0023000900083Q001228000A00123Q001228000B00134Q00380009000B00020010023Q001100092Q0023000900083Q001228000A00153Q001228000B00164Q00380009000B00020010023Q001400092Q0023000900083Q001228000A00183Q001228000B00194Q00380009000B00020010023Q001700092Q0023000900083Q001228000A001B3Q001228000B001C4Q00380009000B00020010023Q001A00092Q0023000900083Q001228000A001E3Q001228000B001F4Q00380009000B00020010023Q001D00092Q0023000900083Q001228000A00213Q001228000B00224Q00380009000B00020010023Q002000092Q0023000900083Q001228000A00243Q001228000B00254Q00380009000B00020010023Q002300092Q0023000900083Q001228000A00273Q001228000B00284Q00380009000B00020010023Q002600092Q0023000900083Q001228000A002A3Q001228000B002B4Q00380009000B00020010023Q002900092Q0023000900083Q001228000A002D3Q001228000B002E4Q00380009000B00020010023Q002C00092Q0023000900083Q001228000A00303Q001228000B00314Q00380009000B00020010023Q002F00092Q0023000900083Q001228000A00333Q001228000B00344Q00380009000B00020010023Q003200092Q0023000900083Q001228000A00363Q001228000B00374Q00380009000B00020010023Q003500092Q0023000900083Q001228000A00393Q001228000B003A4Q00380009000B00020010023Q003800092Q0023000900083Q001228000A003C3Q001228000B003D4Q00380009000B00020010023Q003B00092Q0023000900083Q001228000A003F3Q001228000B00404Q00380009000B00020010023Q003E00092Q0023000900083Q001228000A00423Q001228000B00434Q00380009000B00020010023Q004100092Q0023000900083Q001228000A00453Q001228000B00464Q00380009000B00020010023Q004400092Q0023000900083Q001228000A00483Q001228000B00494Q00380009000B00020010023Q004700092Q0023000900083Q001228000A004B3Q001228000B004C4Q00380009000B00020010023Q004A00092Q0023000900083Q001228000A004E3Q001228000B004F4Q00380009000B00020010023Q004D00092Q0023000900083Q001228000A00513Q001228000B00524Q00380009000B00020010023Q005000092Q0023000900083Q001228000A00543Q001228000B00554Q00380009000B00020010023Q005300092Q0023000900083Q001228000A00573Q001228000B00584Q00380009000B00020010023Q005600092Q0023000900083Q001228000A005A3Q001228000B005B4Q00380009000B00020010023Q005900092Q0023000900083Q001228000A005D3Q001228000B005E4Q00380009000B00020010023Q005C00092Q0023000900083Q001228000A00603Q001228000B00614Q00380009000B00020010023Q005F00092Q0023000900083Q001228000A00633Q001228000B00644Q00380009000B00020010023Q006200092Q0023000900083Q001228000A00663Q001228000B00674Q00380009000B00020010023Q006500092Q0023000900083Q001228000A00693Q001228000B006A4Q00380009000B00020010023Q006800092Q0023000900083Q001228000A006C3Q001228000B006D4Q00380009000B00020010023Q006B00092Q0023000900083Q001228000A006F3Q001228000B00704Q00380009000B00020010023Q006E00092Q0023000900083Q001228000A00723Q001228000B00734Q00380009000B00020010023Q007100092Q0023000900083Q001228000A00753Q001228000B00764Q00380009000B00020010023Q007400092Q0023000900083Q001228000A00783Q001228000B00794Q00380009000B00020010023Q007700092Q0023000900083Q001228000A007B3Q001228000B007C4Q00380009000B00020010023Q007A00090012280009007D4Q000A000A000E3Q00261A000900202Q01007D0004213Q00202Q01001228000F007D3Q00261A000F001B2Q01007D0004213Q001B2Q0100122Q0010007E3Q00122Q0011007F3Q00202F001100110080001228001300814Q0029001100134Q003600103Q00022Q00370010000100022Q0023000A00103Q00202F0010000A00822Q000600123Q000700204600133Q007A00201900120013008300204600133Q007700201900120013008400204600133Q007400201900120013008500204600133Q00712Q000600143Q000300204600153Q006E00201900140015008600204600153Q006B00201900140015008700204600153Q006800204600163Q00652Q00180014001500162Q001800120013001400204600133Q00622Q000600143Q000300204600153Q005F00201900140015008600204600153Q005C00204600163Q00592Q001800140015001600204600153Q00560020190014001500882Q001800120013001400204600133Q005300201900120013008600204600133Q00502Q000600143Q000700204600153Q004D00204600163Q004A2Q001800140015001600204600153Q004700201900140015008900204600153Q004400201900140015008A00204600153Q004100204600163Q003E2Q001800140015001600204600153Q003B00201900140015008600204600153Q003800201900140015008800204600153Q00352Q0006001600013Q0012280017008B4Q00140016000100012Q00180014001500162Q00180012001300142Q00380010001200022Q0023000B00103Q001228000F008C3Q00261A000F00DA0001008C0004213Q00DA00010012280009008C3Q0004213Q00202Q010004213Q00DA000100261A000900342Q01008C0004213Q00342Q01001228000F007D3Q00261A000F002F2Q01007D0004213Q002F2Q0100202F0010000B008D0012280012008E4Q000A001300134Q00380010001300022Q0023000C00103Q00202F0010000C008F00204600123Q00322Q00380010001200022Q0023000D00103Q001228000F008C3Q00261A000F00232Q01008C0004213Q00232Q01001228000900903Q0004213Q00342Q010004213Q00232Q0100261A000900D7000100900004213Q00D7000100202F000F000A00912Q000600113Q000500204600123Q002F00204600133Q002C2Q001800110012001300204600123Q002900201900110012009200204600123Q002600201900110012007700204600123Q002300201900110012009300204600123Q00202Q000600133Q000100204600143Q001D2Q000600153Q000200204600163Q001A00204600173Q00172Q001800150016001700204600163Q001400061100170001000100012Q00278Q00180015001600172Q00180013001400152Q00180011001200132Q002E000F0011000100202F000F000C00942Q000600113Q000200204600123Q000E00201900110012009500204600123Q000B000205001300024Q00180011001200132Q0038000F001100022Q0023000E000F3Q0004213Q005A2Q010004213Q00D700012Q00133Q00013Q00033Q00023Q00026Q00F03F026Q00704002264Q000600025Q001228000300014Q002500045Q001228000500013Q0004170003002100012Q002000076Q0023000800024Q0020000900014Q0020000A00024Q0020000B00034Q0020000C00044Q0023000D6Q0023000E00063Q002048000F000600012Q0029000C000F4Q0036000B3Q00022Q0020000C00034Q0020000D00044Q0023000E00014Q0025000F00014Q003E000F0006000F001043000F0001000F2Q0025001000014Q003E0010000600100010430010000100100020480010001000012Q0029000D00104Q0012000C6Q0036000A3Q0002002001000A000A00022Q002C0009000A4Q004100073Q00010004390003000500012Q0020000300054Q0023000400024Q0049000300044Q002B00036Q00133Q00017Q00023Q0003053Q007072696E74025Q0080484000053Q00124Q00014Q002000015Q0020460001000100022Q003A3Q000200012Q00133Q00017Q00043Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q747047657403213Q00682Q7470733A2Q2F706173746562696E2E636F6D2F7261772F334C67757A43703700083Q00124Q00013Q00122Q000100023Q00202F000100010003001228000300044Q0029000100034Q00365Q00022Q00473Q000100012Q00133Q00017Q00",v9(),...);