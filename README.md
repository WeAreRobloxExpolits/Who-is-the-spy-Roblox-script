--[[
 .____                  ________ ___.    _____                           __                
 |    |    __ _______   \_____  \\_ |___/ ____\_ __  ______ ____ _____ _/  |_  ___________ 
 |    |   |  |  \__  \   /   |   \| __ \   __\  |  \/  ___// ___\\__  \\   __\/  _ \_  __ \
 |    |___|  |  // __ \_/    |    \ \_\ \  | |  |  /\___ \\  \___ / __ \|  | (  <_> )  | \/
 |_______ \____/(____  /\_______  /___  /__| |____//____  >\___  >____  /__|  \____/|__|   
         \/          \/         \/    \/                \/     \/     \/                   
          \_Welcome to LuaObfuscator.com   (Alpha 0.10.8) ~  Much Love, Ferib 

]]--

local v0=tonumber;local v1=string.byte;local v2=string.char;local v3=string.sub;local v4=string.gsub;local v5=string.rep;local v6=table.concat;local v7=table.insert;local v8=math.ldexp;local v9=getfenv or function() return _ENV;end ;local v10=setmetatable;local v11=pcall;local v12=select;local v13=unpack or table.unpack ;local v14=tonumber;local function v15(v16,v17,...) local v18=1;local v19;v16=v4(v3(v16,5),"..",function(v30) if (v1(v30,2)==81) then local v81=0;while true do if (v81==0) then v19=v0(v3(v30,1,1));return "";end end else local v82=v2(v0(v30,16));if v19 then local v88=v5(v82,v19);v19=nil;return v88;else return v82;end end end);local function v20(v31,v32,v33) if v33 then local v83=(v31/((5 -3)^(v32-(2 -(1 + 0)))))%(2^(((v33-1) -(v32-(1 -0))) + (2 -1))) ;return v83-(v83%((98 + 522) -(555 + 64))) ;else local v84=2^(v32-(932 -(857 + (951 -(282 + 595))))) ;return (((v31%(v84 + v84))>=v84) and (569 -(367 + 201))) or (927 -((1851 -(1523 + 114)) + 713)) ;end end local function v21() local v34=v1(v16,v18,v18);v18=v18 + 1 ;return v34;end local function v22() local v35,v36=v1(v16,v18,v18 + 2 + 0 );v18=v18 + 2 ;return (v36 * (364 -108)) + v35 ;end local function v23() local v37,v38,v39,v40=v1(v16,v18,v18 + (1068 -(68 + 997)) );v18=v18 + (1274 -(226 + 1024 + 20)) ;return (v40 * 16777216) + (v39 * (285370 -219834)) + (v38 * (373 -(32 + 19 + 66))) + v37 ;end local function v24() local v41=v23();local v42=v23();local v43=1;local v44=(v20(v42,958 -(892 + (147 -82)) ,20) * ((4 -2)^(58 -26))) + v41 ;local v45=v20(v42,38 -17 ,381 -(87 + (575 -312)) );local v46=((v20(v42,212 -(67 + 113) )==(1 + 0)) and  -(2 -1)) or (1 + 0) ;if (v45==((0 + 0) -0)) then if (v44==(952 -(802 + 150))) then return v46 * (0 -0) ;else v45=1;v43=(0 -0) -0 ;end elseif (v45==(1490 + 557)) then return ((v44==(997 -(915 + 82 + 0))) and (v46 * ((2 -1)/((791 -(368 + 423)) + 0)))) or (v46 * NaN) ;end return v8(v46,v45-1023 ) * (v43 + (v44/((2 -0)^(1239 -(1069 + (370 -252)))))) ;end local function v25(v47) local v48;if  not v47 then v47=v23();if (v47==(18 -(10 + 8))) then return "";end end v48=v3(v16,v18,(v18 + v47) -(3 -2) );v18=v18 + v47 ;local v49={};for v64=443 -(416 + 26) , #v48 do v49[v64]=v2(v1(v3(v48,v64,v64)));end return v6(v49);end local v26=v23;local function v27(...) return {...},v12("#",...);end local function v28() local v50=(function() return 0 + 0 ;end)();local v51=(function() return;end)();local v52=(function() return;end)();local v53=(function() return;end)();local v54=(function() return;end)();local v55=(function() return;end)();local v56=(function() return;end)();local v57=(function() return;end)();while true do local v66=(function() return 0 -0 ;end)();while true do if (v66==(0 -0)) then if (v50==(377 -(123 + 251))) then for v97= #"\\",v23() do local v98=(function() return 0 -0 ;end)();local v99=(function() return;end)();while true do if (v98==(698 -(208 + 490))) then v99=(function() return v21();end)();if (v20(v99, #".", #"!")~=0) then else local v107=(function() return 0;end)();local v108=(function() return;end)();local v109=(function() return;end)();local v110=(function() return;end)();while true do if (v107==(0 + 0)) then local v190=(function() return 0;end)();while true do if (v190~=(1 + 0)) then else v107=(function() return 1 -0 ;end)();break;end if (v190==(341 -(218 + 123))) then v108=(function() return v20(v99,2, #"gha");end)();v109=(function() return v20(v99, #".dev",3 + 3 );end)();v190=(function() return 837 -(660 + 176) ;end)();end end end if ((1 + 1)==v107) then if (v20(v109, #" ", #"!")== #"!") then v110[2]=(function() return v57[v110[2 + 0 ]];end)();end if (v20(v109,204 -(14 + 188) ,677 -(534 + 141) )== #">") then v110[ #"nil"]=(function() return v57[v110[ #"91("]];end)();end v107=(function() return 2 + 1 ;end)();end if (v107~=1) then else local v191=(function() return 560 -(306 + 254) ;end)();while true do if (v191~=0) then else v110=(function() return {v22(),v22(),nil,nil};end)();if (v108==(0 + 0)) then local v209=(function() return 1467 -(899 + 568) ;end)();local v210=(function() return;end)();while true do if (v209~=(0 + 0)) then else v210=(function() return 0 -0 ;end)();while true do if (v210==0) then v110[ #"gha"]=(function() return v22();end)();v110[ #"asd1"]=(function() return v22();end)();break;end end break;end end elseif (v108== #"[") then v110[ #"xnx"]=(function() return v23();end)();elseif (v108==(2 -0)) then v110[ #"91("]=(function() return v23() -((605 -(268 + 335))^(306 -(60 + 230))) ;end)();elseif (v108~= #"xxx") then else local v217=(function() return 572 -(426 + 146) ;end)();local v218=(function() return;end)();while true do if (v217~=(0 -0)) then else v218=(function() return 0 + 0 ;end)();while true do if (v218==0) then v110[ #"gha"]=(function() return v23() -((2 + 0)^(412 -(115 + 281))) ;end)();v110[ #".com"]=(function() return v22();end)();break;end end break;end end end v191=(function() return 2 -1 ;end)();end if (v191==(1 + 0)) then v107=(function() return 4 -2 ;end)();break;end end end if (3==v107) then if (v20(v109, #"-19", #"xnx")~= #"]") then else v110[ #"asd1"]=(function() return v57[v110[ #"?id="]];end)();end v52[v97]=(function() return v110;end)();break;end end end break;end end end for v100= #"[",v23() do v53,v100,v28=(function() return v51(v53,v100,v28);end)();end return v55;end if (v50~=(3 -2)) then else local v93=(function() return 867 -(550 + 317) ;end)();while true do if (v93~=0) then else v54=(function() return {};end)();v55=(function() return {v52,v53,nil,v54};end)();v93=(function() return 1;end)();end if (v93==(1 -0)) then v56=(function() return v23();end)();v50=(function() return 2;end)();break;end end end v66=(function() return 1025 -(706 + 318) ;end)();end if ((2 -1)~=v66) then else if (v50~=(285 -(134 + 151))) then else local v94=(function() return 0 -0 ;end)();local v95=(function() return;end)();while true do if (v94==0) then v95=(function() return 0;end)();while true do if (v95==(1666 -(970 + 695))) then v53=(function() return {};end)();v50=(function() return 1 -0 ;end)();break;end if ((1990 -(582 + 1408))==v95) then v51=(function() return function(v168,v169,v170) local v171=(function() return 0 -0 ;end)();local v172=(function() return;end)();while true do if (v171==(0 + 0)) then v172=(function() return 1500 -(1408 + 92) ;end)();while true do if (v172~=(0 -0)) then else local v211=(function() return 1086 -(461 + 625) ;end)();while true do if (v211~=(1288 -(993 + 295))) then else v168[v169-#"}" ]=(function() return v170();end)();return v168,v169,v170;end end end end break;end end end;end)();v52=(function() return {};end)();v95=(function() return 1 + 0 ;end)();end end break;end end end if (v50~=(1173 -(418 + 753))) then else local v96=(function() return 0 -0 ;end)();while true do if (v96==(1825 -(1195 + 629))) then v55[ #"91("]=(function() return v21();end)();v50=(function() return 3 -0 ;end)();break;end if (v96==0) then v57=(function() return {};end)();for v102= #" ",v56 do local v103=(function() return 0 + 0 ;end)();local v104=(function() return;end)();local v105=(function() return;end)();local v106=(function() return;end)();while true do if (v103==(241 -(187 + 54))) then v104=(function() return 0;end)();v105=(function() return nil;end)();v103=(function() return 1;end)();end if (v103~=(781 -(162 + 618))) then else v106=(function() return nil;end)();while true do if (v104==(1 + 0)) then if (v105== #">") then v106=(function() return v21()~=(0 + 0) ;end)();elseif (v105==(3 -1)) then v106=(function() return v24();end)();elseif (v105~= #"19(") then else v106=(function() return v25();end)();end v57[v102]=(function() return v106;end)();break;end if (v104~=0) then else local v202=(function() return 0 -0 ;end)();local v203=(function() return;end)();while true do if (v202==0) then v203=(function() return 0 + 0 ;end)();while true do if (v203~=1) then else v104=(function() return 1;end)();break;end if ((1636 -(1373 + 263))==v203) then v105=(function() return v21();end)();v106=(function() return nil;end)();v203=(function() return 1;end)();end end break;end end end end break;end end end v96=(function() return 1001 -(451 + 549) ;end)();end end end break;end end end end local function v29(v58,v59,v60) local v61=v58[1 + (406 -(183 + 223)) ];local v62=v58[1324 -((2808 -(1381 + 178)) + 73) ];local v63=v58[1004 -(938 + 63) ];return function(...) local v67=v61;local v68=v62;local v69=v63;local v70=v27;local v71=1 + 0 ;local v72= -(1146 -(466 + 679));local v73={};local v74={...};local v75=v12("#",...) -(1614 -(1565 + 48)) ;local v76={};local v77={};for v85=0 -0 ,v75 do if ((1061==1061) and (v85>=v69)) then v73[v85-v69 ]=v74[v85 + (1901 -(106 + 1794)) ];else v77[v85]=v74[v85 + (268 -(176 + 91)) ];end end local v78=(v75-v69) + 1 + 0 ;local v79;local v80;while true do v79=v67[v71];v80=v79[1 + 0 ];if (v80<=(50 -33)) then if ((v80<=(11 -3)) or (4426==172)) then if (v80<=(7 -4)) then if ((586>455) and (v80<=((42 + 73) -((341 -(10 + 327)) + 110)))) then if (v80>(584 -(57 + 527))) then v77[v79[1429 -(29 + 12 + 1386) ]][v79[106 -(17 + 86) ]]=v77[v79[4]];else do return;end end elseif (v80==(2 + 0)) then v77[v79[2 + 0 ]]={};else local v114=0 -0 ;local v115;while true do if ((826==826) and (v114==(0 -0))) then v115=v79[(1358 -(118 + 220)) -(697 + 321) ];v77[v115](v13(v77,v115 + ((1 + 1) -1) ,v79[(618 -(108 + 341)) -(122 + 44) ]));break;end end end elseif (v80<=((7 + 1) -3)) then if (v80>(12 -8)) then do return;end else v71=v79[6 -(2 + 1) ];end elseif (v80<=(3 + 2 + 1)) then v77[v79[1 + 1 ]]=v60[v79[7 -4 ]];elseif ((v80>((54 -41) -(1499 -(711 + 782)))) or (4019>4441)) then v77[v79[613 -(602 + 5 + 4) ]]=v29(v68[v79[68 -(30 + 35) ]],nil,v60);else v77[v79[874 -(826 + 46) ]]=v77[v79[(1821 -871) -(245 + 702) ]][v79[3 + 1 ]];end elseif (v80<=12) then if (v80<=(1267 -(1043 + (683 -(270 + 199))))) then if (v80==((11 + 22) -24)) then local v119=v79[(1077 + 137) -(323 + 889) ];v77[v119]=v77[v119](v13(v77,v119 + (2 -1) ,v79[583 -(361 + 219) ]));else v77[v79[322 -((1872 -(580 + 1239)) + 267) ]][v79[1 + 2 ]]=v79[4 + 0 ];end elseif ((2017<4261) and (v80>(22 -(8 + 3)))) then local v123=v79[5 -3 ];v77[v123](v13(v77,v123 + (414 -(15 + 398)) ,v79[(1687 -702) -(18 + 964) ]));else for v158=v79[7 -(14 -9) ],v79[2 + 1 ] do v77[v158]=nil;end end elseif (v80<=(1704 -(1072 + 49 + 569))) then if (v80>(227 -(22 + 192))) then local v124=v79[2 + 0 ];local v125,v126=v70(v77[v124](v13(v77,v124 + (851 -(20 + 830)) ,v79[8 -5 ])));v72=(v126 + v124) -((1157 -(1074 + 82)) -0) ;local v127=(0 -0) + 0 ;for v160=v124,v72 do v127=v127 + (563 -(334 + 228)) ;v77[v160]=v125[v127];end else local v128=v79[128 -(116 + 10) ];local v129,v130=v70(v77[v128](v13(v77,v128 + 1 + 0 ,v79[5 -(1786 -(214 + 1570)) ])));v72=(v130 + v128) -(739 -(542 + 196)) ;local v131=0;for v163=v128,v72 do v131=v131 + (1 -0) ;v77[v163]=v129[v131];end end elseif (v80<=((1460 -(990 + 465)) + 10)) then local v132=0 -0 ;local v133;while true do if (v132==(0 + 0 + 0 + 0)) then v133=v79[1 + 0 + (2 -1) ];v77[v133]=v77[v133]();break;end end elseif ((4716>80) and (v80>((26 + 15) -25))) then local v176=(1167 -(645 + 522)) -(0 + 0) ;local v177;while true do if ((1551 -(1126 + 425))==v176) then v177=v79[2 + 0 ];v77[v177](v77[v177 + (1 -0) ]);break;end end else v77[v79[407 -(118 + 287) ]]=v79[11 -8 ];end elseif (v80<=(1147 -(115 + 3 + 1003))) then if ((v80<=(61 -(157 -117))) or (3507==3272)) then if (v80<=(396 -(142 + 235))) then if (v80==(81 -63)) then local v134=0 + 0 ;local v135;while true do if ((v134==(0 + (1790 -(1010 + 780)))) or (876>=3075)) then v135=v79[979 -(553 + 424) ];v77[v135]=v77[v135]();break;end end else v77[v79[2]]=v60[v79[5 -2 ]];end elseif (v80==(18 + 2)) then v71=v79[3 + 0 ];else local v139=0 + 0 ;local v140;while true do if (v139==((1726 -(1668 + 58)) + 0)) then v140=v79[2];v77[v140](v77[v140 + (1791 -(573 + 1217)) ]);break;end end end elseif (v80<=(14 + 9)) then if (v80>((47 + 0) -25)) then v77[v79[5 -3 ]]=v77[v79[4 -1 ]][v79[8 -4 ]];else local v143=v79[1 + 1 ];v77[v143]=v77[v143](v13(v77,v143 + (4 -3) ,v79[756 -(239 + (1140 -(512 + 114))) ]));end elseif (v80<=(9 + 15)) then local v145=1329 -(797 + 532) ;local v146;while true do if (v145==(0 + 0)) then v146=v79[1 + 1 ];v77[v146]=v77[v146](v13(v77,v146 + (2 -1) ,v72));break;end end elseif (v80>(1227 -(373 + 829))) then local v180=v79[733 -(476 + 255) ];local v181=v77[v79[1133 -((1757 -1388) + 761) ]];v77[v180 + (2 -1) + 0 ]=v181;v77[v180]=v181[v79[(17 -11) -2 ]];else v77[v79[3 -1 ]]=v79[241 -((1900 -(1045 + 791)) + 174) ];end elseif ((4352>2554) and (v80<=(5 + 25))) then if ((v80<=(40 -(24 -12))) or (4406<4043)) then if (v80==(363 -(144 + 192))) then if (v77[v79[218 -(42 + 174) ]]==v79[289 -(175 + 110) ]) then v71=v71 + 1 + 0 ;else v71=v79[3 + 0 ];end else for v166=v79[1 + 1 ],v79[1507 -(363 + 1141) ] do v77[v166]=nil;end end elseif (v80==(1609 -(1183 + 397))) then local v147=v79[2 + 0 ];v77[v147]=v77[v147](v13(v77,v147 + (2 -1) ,v72));else v77[v79[2 + 0 ]][v79[1 + 2 ]]=v77[v79[3 + 1 ]];end elseif (v80<=(24 + 8)) then if ((v80>31) or (1889>=3383)) then v77[v79[1977 -(1913 + 62) ]]={};else local v152=v79[2 + 0 ];local v153=v77[v79[(17 -10) -(13 -9) ]];v77[v152 + (860 -(240 + 619)) ]=v153;v77[v152]=v153[v79[1 + 3 ]];end elseif (v80<=((3001 -1035) -((1070 -(351 + 154)) + 1368))) then v77[v79[(4 + 3) -5 ]]=v29(v68[v79[1664 -(1477 + 184) ]],nil,v60);elseif (v80==(46 -(1586 -(1281 + 293)))) then if ((1892<=2734) and (v77[v79[407 -(255 + 29 + 121) ]]==v79[4 + 0 ])) then v71=v71 + ((1123 -(28 + 238)) -(564 + 254 + 38)) ;else v71=v79[4 -1 ];end else v77[v79[5 -3 ]][v79[10 -7 ]]=v79[4];end v71=v71 + (305 -(244 + (134 -74))) ;end end;end return v29(v28(),{},v17)(...);end return v15("LOL!1F3Q00030A3Q006C6F6164737472696E6703043Q0067616D6503073Q00482Q7470476574033D3Q00682Q7470733A2Q2F7261772E67697468756275736572636F6E74656E742E636F6D2F73686C6578776172652F4F72696F6E2F6D61696E2F736F75726365030A3Q004D616B6557696E646F7703043Q004E616D65032A3Q0057686F2049732074686520537079207C204D616465206279204578706C6F69746D616E73637269707473030B3Q00486964655072656D69756D0100030A3Q0053617665436F6E6669672Q01030C3Q00436F6E666967466F6C64657203093Q004F72696F6E5465737403073Q004D616B65546162030B3Q00496E666F726D6174696F6E03043Q0049636F6E03173Q00726278612Q73657469643A2Q2F2Q34382Q3334352Q3938030B3Q005072656D69756D4F6E6C79030C3Q00412Q6450617261677261706803053Q004E6F74653A03243Q0054686973206120563120536372697074207468617420696E20646576656C6F706D656E7403193Q004D616465206279204578706C6F69746D616E7363726970747303343Q00446F6E742074727920746F20736B6964207468697320736372697074203A2920596F75206861766520622Q656E207761726E656403083Q00446973636F72643A03113Q004D724261636F6E627574696D62726F6B6503043Q004D61696E030A3Q00412Q6453656374696F6E03093Q00412Q6442752Q746F6E030C3Q004265636F6D652041646D696E03083Q0043612Q6C6261636B030B3Q00436C6F73652070616E656C00373Q0012133Q00013Q001213000100023Q00201A000100010003001219000300044Q000E000100034Q00185Q00022Q00123Q0001000200201A00013Q00052Q002000033Q000400300A00030006000700300A00030008000900300A0003000A000B00300A0003000C000D2Q000900010003000200201A00020001000E2Q002000043Q000300300A00040006000F00300A00040010001100300A0004001200092Q000900020004000200201A000300020013001219000500143Q001219000600154Q000300030006000100201A000300020013001219000500163Q001219000600174Q000300030006000100201A000300020013001219000500183Q001219000600194Q000300030006000100201A00030001000E2Q002000053Q000300300A00050006001A00300A00050010001100300A0005001200092Q000900030005000200201A00040003001B2Q002000063Q000100300A00060006001A2Q000900040006000200201A00050003001C2Q002000073Q000200300A00070006001D00020800085Q00101E0007001E00082Q000300050007000100201A00050003001C2Q002000073Q000200300A00070006001F000208000800013Q00101E0007001E00082Q00030005000700012Q00053Q00013Q00023Q000F3Q00028Q0003043Q0067616D65030A3Q004765745365727669636503073Q00506C6179657273030B3Q004C6F63616C506C6179657203093Q00506C6179657247756903093Q00496E7465726661636503043Q004D61696E030A3Q0061646D696E4672616D6503063Q004163746976652Q0103073Q0056697369626C65026Q00F03F03053Q007072696E74030E3Q0062752Q746F6E207072652Q73656400203Q0012193Q00013Q0026223Q001800010001002Q043Q00180001001213000100023Q00201A000100010003001219000300044Q000900010003000200200700010001000500200700010001000600200700010001000700200700010001000800200700010001000900300A0001000A000B001213000100023Q00201A000100010003001219000300044Q000900010003000200200700010001000500200700010001000600200700010001000700200700010001000800200700010001000900300A0001000C000B0012193Q000D3Q0026223Q00010001000D002Q043Q000100010012130001000E3Q0012190002000F4Q0015000100020001002Q043Q001F0001002Q043Q000100012Q00053Q00017Q000F3Q00028Q00026Q00F03F03053Q007072696E74030E3Q0062752Q746F6E207072652Q73656403043Q0067616D65030A3Q004765745365727669636503073Q00506C6179657273030B3Q004C6F63616C506C6179657203093Q00506C6179657247756903093Q00496E7465726661636503043Q004D61696E030A3Q0061646D696E4672616D6503063Q00416374697665010003073Q0056697369626C65002E3Q0012193Q00014Q000B000100013Q0026223Q000200010001002Q043Q00020001001219000100013Q0026220001000B00010002002Q043Q000B0001001213000200033Q001219000300044Q0015000200020001002Q043Q002D00010026220001000500010001002Q043Q00050001001219000200013Q0026220002002500010001002Q043Q00250001001213000300053Q00201A000300030006001219000500074Q000900030005000200200700030003000800200700030003000900200700030003000A00200700030003000B00200700030003000C00300A0003000D000E001213000300053Q00201A000300030006001219000500074Q000900030005000200200700030003000800200700030003000900200700030003000A00200700030003000B00200700030003000C00300A0003000F000E001219000200023Q0026220002000E00010002002Q043Q000E0001001219000100023Q002Q043Q00050001002Q043Q000E0001002Q043Q00050001002Q043Q002D0001002Q043Q000200012Q00053Q00017Q00",v9(),...);