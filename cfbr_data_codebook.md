# CODEBOOK - CFBR

## TABLES
 - [Enrollment](#table_1)
 - [Samples](#table_2)
 - [CRF](#table_3)
 - [Bacterial Isolates](#table_4)
 - [Glucose Status and OGTT Results](#table_5)
 - [CGM-CRF](#table_6)


#### <span id="table_1">1. Enrollment</span>

| Variable Name | Details | Values |
| :---- | :---- | :---- |
| cfbr_id | CF-BR number of patient CFBR-EM/AU-XXXX |  |
| subject_status | Subject Status | 1: Cystic Fibrosis <br> 2: CFTR Related Disorder <br> 3: CRMS <br> 4: Non-CF Pulmonary Disease <br> 5: CF Carrier <br> 6: Healthy Control |
| port_cf_id | PortCF ID || 
| name | Name || 
| enrollment_location | Enrollment Location | 1: Emory University <br> 2: Augusta University | 
| has_a_medical_record | Does subject have a medical record? | 0: No <br> 1: Yes |
| medical_record_mrn_EPIC | Medical Record MRN#: EPIC | 0: False <br> 1: True | 
| medical_record_mrn_Powerchart | Medical Record MRN#: Powerchart | 0: False <br> 1: True | 
| epic_mrn | EPIC MRN# || 
| powerchart_mrn | Powerchart MRN# || 
| dob | Date of Birth ||
| sex | Sex ||
| race_black_or_african_american | Black or African-American | 0: False <br> 1: True |
| race_asian | Asian | 0: False <br> 1: True |
| race_white_or_caucasian | White or Caucasian | 0: False <br> 1: True |
| race_american_indian_or_alaska_native | American Indian or Alaska Native | 0: False <br> 1: True |
| race_native_hawaiian_or_other_pacific_islander | Native Hawaiian or Other Pacific Islander | 0: False <br> 1: True |
| race_unknown_or_not_reported | Unknown or Not Reported | 0: False <br> 1: True |
| race_Other | Other | 0: False <br> 1: True |
| race_Other_type | Type of 'race_Other' if race_Other is True ||
| ethnicity | Ethnicity | 1: Hispanic or Latino <br> 2: Not Hispanic or Latino <br> 3: Unknown or Not Reported |
| date_consented | Date Consented |yyyy-mm-dd|
| reconsented | Date Reconsented |yyyy-mm-dd|
| blood | Blood | 1: Up to 5 times per year <br> 2: Once <br> 3: Never |
| ebc | EBC | 1: Up to 5 times per year <br> 2: Once <br> 3: Never |
| nasal_cells | Nasal Cells | 1: Up to 5 times per year <br> 2: Once <br> 3: Never | 
| expectorated_sputum | Expectorated Sputum | 1: Up to 5 times per year <br> 2: Once <br> 3: Never |
| induced_sputum | Induced Sputum | 1: Up to 5 times per year <br> 2: Once <br> 3: Never |
| throat_swab | Throat Swab | 1: Up to 5 times per year <br> 2: Once <br> 3: Never |
| bacterial_isolates | Bacterial Isolates | 1: Up to 5 times per year <br> 2: Once <br> 3: Never |
| genetics_consent | Genetics Consent | 1: Consented <br> 2: Declined <br> 3: Not approached |
| genetics_consent_date | Date Genetics Consent Signed |yyyy-mm-dd|
| longitudinal_neutrophil_consent | Longitudinal Neutrophil Consent |1: Consented <br> 2: Declined <br> 3: Not approached |
| date_neutrophil_consent_fo | Date Nuetrophil Consent Form Signed |yyyy-mm-dd|
| bal_consent | BAL Consent | 0: No <br> 1: Yes |
| mutation_1 | Mutation 1 | 1: 457TAT->G <br> 2: 712-1G->T <br> 3: 1248+1G->A <br> 4: 663delT <br> 5: 1259insA <br> 6: 2585delT <br> 7: 852del22 <br> 8: 1461ins4 <br> 9: 1898+3A->G <br> 10: 1213delT <br> 11: 1341+1G->A <br> 12: 1548delG <br> 13: 1717-8G->A <br> 14: 3121-1G->A <br> 15: 4209TGTT->AA <br> 16: 1949del84 <br> 17: 2055del9->A <br> 18: 2105-2117del13insAGAAA <br> 19: 2183AA'G <br> 20: 3849+4A->G <br> 21: 4374+1G->T <br> 22: 1288insTA <br> 23: 1342-2A->C <br> 24: 3667ins4 <br> 25: 3821delT <br> 26: 405+3A->C <br> 27: 1161delC <br> 28: 1716G/A <br> 29: 1811+1G->C <br> 30: 1898+5G->T <br> 31: 306insA <br> 32: 3850-1G->A <br> 33: 3850-3T->G <br> 34: 4326delTC <br> 35: 444delA <br> 36: 935delA <br> 37: 1898+1G->T <br> 38: 2043delG <br> 39: 2869insG <br> 40: 2896insAG <br> 41: 300delA <br> 42: 3132delTG <br> 43: 3199del6 <br> 45: 3600+2insT <br> 46: 3737delA <br> 47: 4005+2T->C <br> 48: 4040delA <br> 49: 541delC <br> 50: 621+3A->G <br> 51: CFTRdele2,3 <br> 52: TG12/T5 <br> 53: TG12 <br> 54: CFTRdele22,23 <br> 55: TG10 <br> 56: CFTRdele2 <br> 57: CFTRdele22-24 <br> 58: TG11 <br> 59: CFTRdele19 <br> 60: Delexon17a-17b-18 <br> 67: unknown <br> 68: Other <br> 69: F508del <br> 70: G542X <br> 71: G551D <br> 72: N1303K <br> 73: W1282X <br> 74: R117H <br> 75: R553X <br> 76: R1162X <br> 77: G85E <br> 78: I507del <br> 79: R347P <br> 80: D1152H <br> 81: R560T <br> 82: Q493X <br> 83: E60X <br> 84: R334W <br> 85: Y1092X <br> 86: A455E <br> 87: R1066C <br> 88: R1158X <br> 89: R347H <br> 90: S1251N <br> 91: L206W <br> 92: S549N <br> 93: M1101K <br> 94: Y122X <br> 95: S945L <br> 96: I148T <br> 97: R117C <br> 98: F1074L <br> 99: V520F <br> 100: P67L <br> 101: S1235R <br> 102: T338I <br> 103: G1244E <br> 104: G178R <br> 105: R668C <br> 106: R352Q <br> 107: S549R <br> 108: A559T <br> 109: L1077P <br> 110: M470V <br> 111: W1089X <br> 112: I1027T <br> 113: G576A <br> 114: R75X <br> 115: W846X <br> 116: E585X <br> 117: D1270N <br> 118: Q220X <br> 119: D110H <br> 120: I336K <br> 121: R1066H <br> 122: E822X <br> 123: L997F <br> 124: K710X <br> 125: L1065P <br> 126: Q552X <br> 127: R74W <br> 128: E92X <br> 129: Q39X <br> 130: D579G <br> 131: E831X <br> 132: R75Q <br> 133: Q1313X <br> 134: R709X <br> 135: I1234V <br> 136: R1070Q <br> 137: S466X <br> 138: S489X <br> 139: L467P <br> 140: S492F <br> 141: L927P <br> 142: E92K <br> 143: Q359K/T360K <br> 144: Q890X <br> 145: R764X <br> 146: S1196X <br> 147: W401X <br> 148: F1052V <br> 149: L732X <br> 150: Q98X <br> 151: R1070W <br> 152: R31C <br> 153: R851X <br> 154: W1204X <br> 155: G330X <br> 156: P205S <br> 157: E1104X <br> 158: H199Y <br> 159: Q525X <br> 160: D614G <br> 161: L227R <br> 162: L558S <br> 163: G1069R <br> 164: G970R <br> 165: M1V <br> 166: R1162L <br> 167: R560K <br> 168: S341P <br> 169: S977F <br> 170: V754M <br> 171: Y569D <br> 172: D110E <br> 173: F311del <br> 174: G149R <br> 175: G551S <br> 176: H1054D <br> 177: H139R <br> 178: L1335P <br> 179: L138ins <br> 180: L967S <br> 181: Q1100P <br> 182: Q290X <br> 183: R785X <br> 184: R933G <br> 185: V232D <br> 186: W57G <br> 187: Y563N <br> 188: A561E <br> 189: E116K <br> 190: L165S <br> 191: R792X <br> 192: S1159F <br> 193: S1455X <br> 194: T1246I <br> 195: W496X <br> 196: W57R <br> 197: Y1032C <br> 198: Y109N <br> 199: A46D <br> 200: C276X <br> 201: F311L <br> 202: G1249R <br> 203: G480C <br> 204: G622D <br> 205: G628R(G->A) <br> 206: H939R <br> 207: I175V <br> 208: I502T <br> 209: I506T <br> 210: P574H <br> 211: Q98R <br> 212: R117L <br> 213: S434X <br> 214: S589N <br> 215: V456A <br> 216: E56K <br> 217: G1061R <br> 218: G1349D <br> 219: G673X <br> 220: H609R <br> 221: I1269N <br> 222: I807M <br> 223: L218X <br> 224: M952T <br> 225: P5L <br> 226: Q414X <br> 227: R297Q <br> 228: R334L <br> 229: R560S <br> 230: S1255X <br> 231: S364P <br> 232: S912L <br> 233: S912X <br> 234: T1036N <br> 235: V201M <br> 236: W57X <br> 237: Y563D <br> 238: Y913C <br> 239: 1717-1G->A <br> 240: 621+1G->T <br> 241: 2789+5G->A <br> 242: 3849+10kbC->T <br> 243: 2183AA->G <br> 244: 3120+1G->A <br> 245: 1898+1G->A <br> 246: 3659delC <br> 247: 5T <br> 248: 3272-26A->G <br> 249: 394delTT <br> 250: 2184insA <br> 251: 3905insT <br> 252: 2184delA <br> 253: 1078delT <br> 254: 1154insTC <br> 255: 2183delAA->G <br> 256: 711+1G->T <br> 257: 2143delT <br> 258: 1677delTA <br> 259: 711+5G->A <br> 260: 3120G->A <br> 261: 1811+1.6kbA->G <br> 262: 3876delA <br> 263: 2307insA <br> 264: 4016insT <br> 265: 4382delA <br> 266: 2347delG <br> 267: 2622+1G->A <br> 268: 2789+2insA <br> 269: 3007delG <br> 270: 405+1G->A <br> 271: 406-1G->A <br> 272: 711+3A->G <br> 273: 2711delT <br> 274: 4005+1G->A <br> 275: 574delA <br> 276: 1525-1G->A <br> 277: 1812-1G->A <br> 278: 3791delC <br> 279: 1471delA <br> 280: 1824delA <br> 281: 2118del4 <br> 282: 2556insAT <br> 283: 4015delA <br> 284: 4428insGA <br> 285: 675del4 <br> 286: E1371X <br> 287: Q1412X <br> 288: Y849X <br> 289: Y913X <br> 290: S1255P <br> 291: 1782delA <br> 292: 1898+1G->C <br> 293: 2790-1G->C <br> 294: 297-1G->A <br> 295: 3121-977_3499+248del2515 <br> 296: 2594delGT <br> 297: 7T <br> 298: 2052dupA <br> 299:296+1G>A <br> 300: 5T/11TG <br> 301: None <br> 302: A455V|
| other_mutation_1 | Other ||
| mutation_2 | Mutation 2 | 1: 457TAT->G <br> 2: 712-1G->T <br> 3: 1248+1G->A <br> 4: 663delT <br> 5: 1259insA <br> 6: 2585delT <br> 7: 852del22 <br> 8: 1461ins4 <br> 9: 1898+3A->G <br> 10: 1213delT <br> 11: 1341+1G->A <br> 12: 1548delG <br> 13: 1717-8G->A <br> 14: 3121-1G->A <br> 15: 4209TGTT->AA <br> 16: 1949del84 <br> 17: 2055del9->A <br> 18: 2105-2117del13insAGAAA <br> 19: 2183AA'G <br> 20: 3849+4A->G <br> 21: 4374+1G->T <br> 22: 1288insTA <br> 23: 1342-2A->C <br> 24: 3667ins4 <br> 25: 3821delT <br> 26: 405+3A->C <br> 27: 1161delC <br> 28: 1716G/A <br> 29: 1811+1G->C <br> 30: 1898+5G->T <br> 31: 306insA <br> 32: 3850-1G->A <br> 33: 3850-3T->G <br> 34: 4326delTC <br> 35: 444delA <br> 36: 935delA <br> 37: 1898+1G->T <br> 38: 2043delG <br> 39: 2869insG <br> 40: 2896insAG <br> 41: 300delA <br> 42: 3132delTG <br> 43: 3199del6 <br> 45: 3600+2insT <br> 46: 3737delA <br> 47: 4005+2T->C <br> 48: 4040delA <br> 49: 541delC <br> 50: 621+3A->G <br> 51: CFTRdele2,3 <br> 52: TG12/T5 <br> 53: TG12 <br> 54: CFTRdele22,23 <br> 55: TG10 <br> 56: CFTRdele2 <br> 57: CFTRdele22-24 <br> 58: TG11 <br> 59: CFTRdele19 <br> 60: Delexon17a-17b-18 <br> 67: unknown <br> 68: Other <br> 69: F508del <br> 70: G542X <br> 71: G551D <br> 72: N1303K <br> 73: W1282X <br> 74: R117H <br> 75: R553X <br> 76: R1162X <br> 77: G85E <br> 78: I507del <br> 79: R347P <br> 80: D1152H <br> 81: R560T <br> 82: Q493X <br> 83: E60X <br> 84: R334W <br> 85: Y1092X <br> 86: A455E <br> 87: R1066C <br> 88: R1158X <br> 89: R347H <br> 90: S1251N <br> 91: L206W <br> 92: S549N <br> 93: M1101K <br> 94: Y122X <br> 95: S945L <br> 96: I148T <br> 97: R117C <br> 98: F1074L <br> 99: V520F <br> 100: P67L <br> 101: S1235R <br> 102: T338I <br> 103: G1244E <br> 104: G178R <br> 105: R668C <br> 106: R352Q <br> 107: S549R <br> 108: A559T <br> 109: L1077P <br> 110: M470V <br> 111: W1089X <br> 112: I1027T <br> 113: G576A <br> 114: R75X <br> 115: W846X <br> 116: E585X <br> 117: D1270N <br> 118: Q220X <br> 119: D110H <br> 120: I336K <br> 121: R1066H <br> 122: E822X <br> 123: L997F <br> 124: K710X <br> 125: L1065P <br> 126: Q552X <br> 127: R74W <br> 128: E92X <br> 129: Q39X <br> 130: D579G <br> 131: E831X <br> 132: R75Q <br> 133: Q1313X <br> 134: R709X <br> 135: I1234V <br> 136: R1070Q <br> 137: S466X <br> 138: S489X <br> 139: L467P <br> 140: S492F <br> 141: L927P <br> 142: E92K <br> 143: Q359K/T360K <br> 144: Q890X <br> 145: R764X <br> 146: S1196X <br> 147: W401X <br> 148: F1052V <br> 149: L732X <br> 150: Q98X <br> 151: R1070W <br> 152: R31C <br> 153: R851X <br> 154: W1204X <br> 155: G330X <br> 156: P205S <br> 157: E1104X <br> 158: H199Y <br> 159: Q525X <br> 160: D614G <br> 161: L227R <br> 162: L558S <br> 163: G1069R <br> 164: G970R <br> 165: M1V <br> 166: R1162L <br> 167: R560K <br> 168: S341P <br> 169: S977F <br> 170: V754M <br> 171: Y569D <br> 172: D110E <br> 173: F311del <br> 174: G149R <br> 175: G551S <br> 176: H1054D <br> 177: H139R <br> 178: L1335P <br> 179: L138ins <br> 180: L967S <br> 181: Q1100P <br> 182: Q290X <br> 183: R785X <br> 184: R933G <br> 185: V232D <br> 186: W57G <br> 187: Y563N <br> 188: A561E <br> 189: E116K <br> 190: L165S <br> 191: R792X <br> 192: S1159F <br> 193: S1455X <br> 194: T1246I <br> 195: W496X <br> 196: W57R <br> 197: Y1032C <br> 198: Y109N <br> 199: A46D <br> 200: C276X <br> 201: F311L <br> 202: G1249R <br> 203: G480C <br> 204: G622D <br> 205: G628R(G->A) <br> 206: H939R <br> 207: I175V <br> 208: I502T <br> 209: I506T <br> 210: P574H <br> 211: Q98R <br> 212: R117L <br> 213: S434X <br> 214: S589N <br> 215: V456A <br> 216: E56K <br> 217: G1061R <br> 218: G1349D <br> 219: G673X <br> 220: H609R <br> 221: I1269N <br> 222: I807M <br> 223: L218X <br> 224: M952T <br> 225: P5L <br> 226: Q414X <br> 227: R297Q <br> 228: R334L <br> 229: R560S <br> 230: S1255X <br> 231: S364P <br> 232: S912L <br> 233: S912X <br> 234: T1036N <br> 235: V201M <br> 236: W57X <br> 237: Y563D <br> 238: Y913C <br> 239: 1717-1G->A <br> 240: 621+1G->T <br> 241: 2789+5G->A <br> 242: 3849+10kbC->T <br> 243: 2183AA->G <br> 244: 3120+1G->A <br> 245: 1898+1G->A <br> 246: 3659delC <br> 247: 5T <br> 248: 3272-26A->G <br> 249: 394delTT <br> 250: 2184insA <br> 251: 3905insT <br> 252: 2184delA <br> 253: 1078delT <br> 254: 1154insTC <br> 255: 2183delAA->G <br> 256: 711+1G->T <br> 257: 2143delT <br> 258: 1677delTA <br> 259: 711+5G->A <br> 260: 3120G->A <br> 261: 1811+1.6kbA->G <br> 262: 3876delA <br> 263: 2307insA <br> 264: 4016insT <br> 265: 4382delA <br> 266: 2347delG <br> 267: 2622+1G->A <br> 268: 2789+2insA <br> 269: 3007delG <br> 270: 405+1G->A <br> 271: 406-1G->A <br> 272: 711+3A->G <br> 273: 2711delT <br> 274: 4005+1G->A <br> 275: 574delA <br> 276: 1525-1G->A <br> 277: 1812-1G->A <br> 278: 3791delC <br> 279: 1471delA <br> 280: 1824delA <br> 281: 2118del4 <br> 282: 2556insAT <br> 283: 4015delA <br> 284: 4428insGA <br> 285: 675del4 <br> 286: E1371X <br> 287: Q1412X <br> 288: Y849X <br> 289: Y913X <br> 290: S1255P <br> 291: 1782delA <br> 292: 1898+1G->C <br> 293: 2790-1G->C <br> 294: 297-1G->A <br> 295: 3121-977_3499+248del2515 <br> 296: 2594delGT <br> 297: 7T <br> 298: 296+1G>A <br> 299: 2052dupA <br> 300: 5T/11TG <br> 301: None  <br> 302: A455V |
| other_mutation_2 | Other ||
| mutation_3 | Mutation 3 |1: 457TAT->G <br> 2: 712-1G->T <br> 3: 1248+1G->A <br> 4: 663delT <br> 5: 1259insA <br> 6: 2585delT <br> 7: 852del22 <br> 8: 1461ins4 <br> 9: 1898+3A->G <br> 10: 1213delT <br> 11: 1341+1G->A <br> 12: 1548delG <br> 13: 1717-8G->A <br> 14: 3121-1G->A <br> 15: 4209TGTT->AA <br> 16: 1949del84 <br> 17: 2055del9->A <br> 18: 2105-2117del13insAGAAA <br> 19: 2183AA'G <br> 20: 3849+4A->G <br> 21: 4374+1G->T <br> 22: 1288insTA <br> 23: 1342-2A->C <br> 24: 3667ins4 <br> 25: 3821delT <br> 26: 405+3A->C <br> 27: 1161delC <br> 28: 1716G/A <br> 29: 1811+1G->C <br> 30: 1898+5G->T <br> 31: 306insA <br> 32: 3850-1G->A <br> 33: 3850-3T->G <br> 34: 4326delTC <br> 35: 444delA <br> 36: 935delA <br> 37: 1898+1G->T <br> 38: 2043delG <br> 39: 2869insG <br> 40: 2896insAG <br> 41: 300delA <br> 42: 3132delTG <br> 43: 3199del6 <br> 45: 3600+2insT <br> 46: 3737delA <br> 47: 4005+2T->C <br> 48: 4040delA <br> 49: 541delC <br> 50: 621+3A->G <br> 51: CFTRdele2,3 <br> 52: TG12/T5 <br> 53: TG12 <br> 54: CFTRdele22,23 <br> 55: TG10 <br> 56: CFTRdele2 <br> 57: CFTRdele22-24 <br> 58: TG11 <br> 59: CFTRdele19 <br> 60: Delexon17a-17b-18 <br> 67: unknown <br> 68: Other <br> 69: F508del <br> 70: G542X <br> 71: G551D <br> 72: N1303K <br> 73: W1282X <br> 74: R117H <br> 75: R553X <br> 76: R1162X <br> 77: G85E <br> 78: I507del <br> 79: R347P <br> 80: D1152H <br> 81: R560T <br> 82: Q493X <br> 83: E60X <br> 84: R334W <br> 85: Y1092X <br> 86: A455E <br> 87: R1066C <br> 88: R1158X <br> 89: R347H <br> 90: S1251N <br> 91: L206W <br> 92: S549N <br> 93: M1101K <br> 94: Y122X <br> 95: S945L <br> 96: I148T <br> 97: R117C <br> 98: F1074L <br> 99: V520F <br> 100: P67L <br> 101: S1235R <br> 102: T338I <br> 103: G1244E <br> 104: G178R <br> 105: R668C <br> 106: R352Q <br> 107: S549R <br> 108: A559T <br> 109: L1077P <br> 110: M470V <br> 111: W1089X <br> 112: I1027T <br> 113: G576A <br> 114: R75X <br> 115: W846X <br> 116: E585X <br> 117: D1270N <br> 118: Q220X <br> 119: D110H <br> 120: I336K <br> 121: R1066H <br> 122: E822X <br> 123: L997F <br> 124: K710X <br> 125: L1065P <br> 126: Q552X <br> 127: R74W <br> 128: E92X <br> 129: Q39X <br> 130: D579G <br> 131: E831X <br> 132: R75Q <br> 133: Q1313X <br> 134: R709X <br> 135: I1234V <br> 136: R1070Q <br> 137: S466X <br> 138: S489X <br> 139: L467P <br> 140: S492F <br> 141: L927P <br> 142: E92K <br> 143: Q359K/T360K <br> 144: Q890X <br> 145: R764X <br> 146: S1196X <br> 147: W401X <br> 148: F1052V <br> 149: L732X <br> 150: Q98X <br> 151: R1070W <br> 152: R31C <br> 153: R851X <br> 154: W1204X <br> 155: G330X <br> 156: P205S <br> 157: E1104X <br> 158: H199Y <br> 159: Q525X <br> 160: D614G <br> 161: L227R <br> 162: L558S <br> 163: G1069R <br> 164: G970R <br> 165: M1V <br> 166: R1162L <br> 167: R560K <br> 168: S341P <br> 169: S977F <br> 170: V754M <br> 171: Y569D <br> 172: D110E <br> 173: F311del <br> 174: G149R <br> 175: G551S <br> 176: H1054D <br> 177: H139R <br> 178: L1335P <br> 179: L138ins <br> 180: L967S <br> 181: Q1100P <br> 182: Q290X <br> 183: R785X <br> 184: R933G <br> 185: V232D <br> 186: W57G <br> 187: Y563N <br> 188: A561E <br> 189: E116K <br> 190: L165S <br> 191: R792X <br> 192: S1159F <br> 193: S1455X <br> 194: T1246I <br> 195: W496X <br> 196: W57R <br> 197: Y1032C <br> 198: Y109N <br> 199: A46D <br> 200: C276X <br> 201: F311L <br> 202: G1249R <br> 203: G480C <br> 204: G622D <br> 205: G628R(G->A) <br> 206: H939R <br> 207: I175V <br> 208: I502T <br> 209: I506T <br> 210: P574H <br> 211: Q98R <br> 212: R117L <br> 213: S434X <br> 214: S589N <br> 215: V456A <br> 216: E56K <br> 217: G1061R <br> 218: G1349D <br> 219: G673X <br> 220: H609R <br> 221: I1269N <br> 222: I807M <br> 223: L218X <br> 224: M952T <br> 225: P5L <br> 226: Q414X <br> 227: R297Q <br> 228: R334L <br> 229: R560S <br> 230: S1255X <br> 231: S364P <br> 232: S912L <br> 233: S912X <br> 234: T1036N <br> 235: V201M <br> 236: W57X <br> 237: Y563D <br> 238: Y913C <br> 239: 1717-1G->A <br> 240: 621+1G->T <br> 241: 2789+5G->A <br> 242: 3849+10kbC->T <br> 243: 2183AA->G <br> 244: 3120+1G->A <br> 245: 1898+1G->A <br> 246: 3659delC <br> 247: 5T <br> 248: 3272-26A->G <br> 249: 394delTT <br> 250: 2184insA <br> 251: 3905insT <br> 252: 2184delA <br> 253: 1078delT <br> 254: 1154insTC <br> 255: 2183delAA->G <br> 256: 711+1G->T <br> 257: 2143delT <br> 258: 1677delTA <br> 259: 711+5G->A <br> 260: 3120G->A <br> 261: 1811+1.6kbA->G <br> 262: 3876delA <br> 263: 2307insA <br> 264: 4016insT <br> 265: 4382delA <br> 266: 2347delG <br> 267: 2622+1G->A <br> 268: 2789+2insA <br> 269: 3007delG <br> 270: 405+1G->A <br> 271: 406-1G->A <br> 272: 711+3A->G <br> 273: 2711delT <br> 274: 4005+1G->A <br> 275: 574delA <br> 276: 1525-1G->A <br> 277: 1812-1G->A <br> 278: 3791delC <br> 279: 1471delA <br> 280: 1824delA <br> 281: 2118del4 <br> 282: 2556insAT <br> 283: 4015delA <br> 284: 4428insGA <br> 285: 675del4 <br> 286: E1371X <br> 287: Q1412X <br> 288: Y849X <br> 289: Y913X <br> 290: S1255P <br> 291: 1782delA <br> 292: 1898+1G->C <br> 293: 2790-1G->C <br> 294: 297-1G->A <br> 295: 3121-977_3499+248del2515 <br> 296: 2594delGT <br> 297: 7T <br> 298: None <br> 299: 2052 dupA <br> 300: 296+1G>A <br> 301: 5T/11G  <br> 302: A455V |
| other_mutation_3 | Other ||
| current_modulator | Current Modulator | 1: Ivacaftor (Kalydeco) <br> 2: Lumacaftor / Ivacaftor (Orkambi) <br> 3: Tezacaftor / Ivacaftor (Symdeko) <br> 4: Elexacaftor / Tezacaftor / Ivacaftor (Trikafta) <br> 5: None |
| has_a_hemt_history | Does subject have a HEMT History? | 0: No <br> 1: Yes |
| ivacaftor_kalydeco | Ivacaftor (Kalydeco) | 0: No <br> 1: Yes |
| approximate_ivacaftor_star | Approximate Ivacaftor Start Date |  |
| approximate_ivacaftor_end | Approximate Ivacaftor End Date |  |
| kalydeco_ongoing | Ongoing? | 0: False <br> 1: True |
| lumacaftor_ivacaftor_orkam | Lumacaftor / Ivacaftor (Orkambi) | 0: No <br> 1: Yes |
| orkambi_start_date | Approximate Lumacaftor / Ivacaftor Start Date |  |
| orkambi_end_date | Approximate Lumacaftor / Ivacaftor End Date |  |
| orkambi_ongoing | Ongoing? | 0: False <br> 1: True |
| tezacaftor_ivacaftor_symde | Tezacaftor / Ivacaftor (Symdeko) | 0: No <br> 1: Yes |
| symdeko_start_date | Approximate Tezacaftor / Ivacaftor Start Date |  |
| symdeko_end_date | Approximate Tezacaftor / Ivacaftor End Date |  |
| symdeko_ongoing | Ongoing? | 0: False <br> 1: True |
| elexacaftor_tezacaftor_iva | Elexacaftor / Tezacaftor / Ivacaftor (Trikafta) | 0: No <br> 1: Yes |
| trikafta_start_date | Approximate Elexacaftor / Tezacaftor / Ivacaftor Start Date |  |
| trikafta_end_date | Approximate Elexacaftor / Tezacaftor / Ivacaftor End Date |  |
| trikafta_ongoing | Ongoing? | 0: False <br> 1: True |
| current_status | Current Status | 1: Alive <br> 2: Deceased <br> 3: Moved <br> 4: Withdrawn <br> 5: Post Lung Transplant |
| phone_number | Phone Number ||
| email_address | Email Address ||
| preferred_contact_call | Preferred Method of Contact: Call | 0: False <br> 1: True |
| preferred_contact_text | Preferred Method of Contact: Text | 0: False <br> 1: True |
| preferred_contact_email | Preferred Method of Contact: Email | 0: False <br> 1: True |
| comments | Comments ||
| enrollment_complete | Complete? | 1: Incomplete <br> 2: Unverified <br> 3: Complete |




#### <span id="table_2">2. Samples</span>

| Variable Name | Details | Values |
| :---- | :---- | :---- |
| cfbr_id | CF-BR number of patient |  |
| invoice_req | Invoice Reqμred? | 0: No <br> 1: Yes |
| samples_soldyn | Has this aliquot been sold? | 0: No <br> 1: Yes |
| samples_location | Select the recipient | 1: Assem Ziady <br> 2: Balazs Rada <br> 3: Bijean - Tirouvanzium <br> 4: Camilla - Tirouvanzium <br> 5: Osric - Tirouvanziam <br> 6: Chicago <br> 7: Facundo Fernandez <br> 8: John Varga - Goldberg <br> 9: Joshua Chandler - Jones Lab <br> 10: Kostas Konstantinidis <br> 11: Koval Lab <br> 12: Rabin Tirouvanziam <br> 13: Sam - Koval lab <br> 14: Samer Naffouje (U IL) <br> 15: Spyryx/Matt Walker <br> 16: Stauffer/McCarty <br> 17: Susu Zughaier <br> 18: Tangpricha <br> 19: Theresa Gauthier <br> 20: William R. Hunt <br> 21: Wu/McCarty <br> 22: Christopher LaRock <br> 23: Marvin Whiteley <br> 24: Other (Please email Julie with details) <br> 25: Steve Diggle <br> 26: Andres Garcia <br> 27: Joanna Goldberg <br> 28: Sam Brown <br> 29: Malinda Wu <br> 30: Eric Sorscher Lab <br> 31: Dario Dilernia <br> 32: Sample lost <br> 33: Kathryn Oliver <br> 34: Tim Wells  <br> 35: George Beck  <br> 36: Stephen Dolan  <br> 37: Ben Kopp |
| date_coll_sampl | Date Collected ||
| freezer_location | Freezer Location | 1: Emory Children's Center (ECC) <br> 2: Hiller Lab at Center for Advanced Pediatrics(CAP) <br> 3: Chantilly Lab (NDH) <br> |
| aliquot_id | Aliquot ID ||
| sample_type | Sample Type | 1: Bacterial Isolate <br> 2: Bacterial pellet <br> 3: BAL <br> 4: BAL (with proteinase inhibitor) <br> 5: BAL homogenate <br> 6: Blood: Plasma <br> 7: Blood: Serum <br> 8: Blood: Whole <br> 9: EBC <br> 10: Nasal polyp tissue <br> 11: Nasal Scrape <br> 12: None <br> 13: Sputum, unprocessed/whole <br> 14: Sputum homogenate <br> 15: Sputum supernatant without complete <br> 16: Sputum Supernatant with complete <br> 17: Throat Swab <br> 18: Tracheal Aspirate <br> 19: Micro Purity Plate <br> 20: Saliva <br> 21: Stool |
| collected_during_ogtt | Collected During OGTT | 1: Yes <br> 2: No |
| ogtt_time_points_fasting | OGTT Time Points: Fasting | 0: False <br> 1: True |
| ogtt_time_points_30_minutes | OGTT Time Points: 30 Minutes | 0: False <br> 1: True |
| ogtt_time_points_60_minutes | OGTT Time Points: 60 Minutes | 0: False <br> 1: True |
| ogtt_time_points_2_hours | OGTT Time Points: 2 Hours | 0: False <br> 1: True |
| ogtt_time_points_other | OGTT Time Points: Other | 0: False <br> 1: True |
| other_time_point | Other OGTT Time Point ||
| paired_samples | Paired Samples | 1: Yes <br> 0: No |
| paired_samples_collected_plasma | Paired Samples Collected: Plasma | 0: False <br> 1: True |
| paired_samples_collected_serum | Paired Samples Collected: Serum | 0: False <br> 1: True |
| paired_samples_collected_ebc | Paired Samples Collected: EBC | 0: False <br> 1: True |
| paired_samples_collected_nasal_Cells | Paired Samples Collected: Nasal Cells | 0: False <br> 1: True |
| paired_samples_collected_sputum | Paired Samples Collected: Sputum | 0: False <br> 1: True |
| paired_samples_collected_bacterial_Isolates | Paired Samples Collected: Bacterial Isolates | 0: False <br> 1: True |
| paired_samples_collected_bal | Paired Samples Collected: BAL | 0: False <br> 1: True |
| paired_samples_collected_saliva | Paired Samples Collected: Saliva |0: False <br> 1: True |
| paired_samples_collected_stool | Paired Samples Collected: Stool |0: False <br> 1: True |
| paired_samples_collected_throat_swab | Paired Samples Collected: Throat Swab |0: False <br> 1: True |
| volume | Volume ||
| units | Units | 1: μl <br> 2: ml |
| box | Box ||
| position_row | Box Row ||
| box_column | Box Column ||
| comments_samp | Comments ||
| tech_initials | Tech Initials ||
| samples_complete | Complete? | 0:  Incomplete <br> 1:  Unverified <br> 2:  Complete <br> |




#### <span id="table_3">3. CRF</span>

| Variable Name | Details | Values |
| :---- | :---- | :---- |
| cfbr_id | CF-BR number of patient |  |
| collection_date | Collection Date |yyyy-mm-dd |
| collection_site | Collection Site | 1: ECC <br> 2: Egleston Hospital<br> 3: Emory Adult CF Clinic<br> 4: Emory Children's Center<br> 5: Emory Pediatric CF Clinic <br> 6: EU Hospital<br> 7: Scottish Rite Clinic<br> 8: Scottish Rite Hospital<br> 9: CAP |
| visit_type | Visit Type | 1:  Clinic <br> 2:  Hospital <br>3:  Procedure <br> 4:  Research Study |
| crf_age | Age at Collection |  |
| specimen_collected_blood_serum | Specimen Collected is Blood Serum | 0:  False <br>1:  True <br> |
| specimen_collected_blood_plasma | Specimen Collected is Blood Plsdms | 0:  False <br>1:  True <br> |
| specimen_collected_whole | Specimen Collected is Whole Blood | 0:  False <br>1:  True <br> |
| specimen_collected_expectorated_sputum | Specimen Collected is Expectorated Sputum | 0:  False <br>1:  True <br> |
| specimen_collected_induced_sputum | Specimen Collected is Induced Sputum | 0:  False <br>1:  True <br> |
| specimen_collected_EBC | Specimen Collected is EBC | 0:  False <br>1:  True <br> |
| specimen_collected_BAL | Specimen Collected is BAL | 0:  False <br>1:  True <br> |
| specimen_collected_nasal_scrape | Specimen Collected is Nasal Epithelial Cells | 0:  False <br>1:  True <br> |
| specimen_collected_bronchial_brushings | Specimen Collected is Bronchial Brushings | 0:  False <br>1:  True <br> |
| specimen_collected_saliva | Specimen Collected is Saliva | 0:  False <br>1:  True <br> |
| specimen_collected_stool| Specimen Collected is Stool | 0:  False <br>1:  True <br> |
| specimen_collected_throat_swab | Specimen Collected is Throat Swab | 0:  False <br>1:  True <br> |
| time_of_specimen_collection | Time of Blood Collection |  |
| time_of_sputum_collection | Time of Expectorated Sputum Collection |  |
| time_of_induced_sputum_collection | Time of Induced Sputum Collection |  |
| time_of_ebc_collection | Time of EBC Collection |  |
| time_of_bal_collection | Time of BAL Collection |  |
| time_of_nasal_epithelial_collection | Time of Nasal Epithelial Cell Collection |  |
| time_of_bronchial_brushing | Time of Bronchial Brushing Sample Collection |  |
| time_of_saliva | Time of Saliva Sample Collection |  |
| time_of_stool | Time of Stool Sample Collection |  |
| time_of_throat_swab | Time of Throat Swab Sample Collection |  |
| current_clinical_status | Current Clinical Status <br> Clinically Stable = no increase in symptoms, lung exam at baseline, FEV1 w/ 5% of baseline, no new antibiotic therapy of any kind in response to symptoms or tests, no change in standard CF regimen for +/- 21 days.<br> APE Outpatient = subject is experiencing increase in symptoms and/or drop in lung function 5-10% from baseline; prescribed outpatient oral antibiotics. <br> APE IV Antibiotics = increased symptoms and/or drop in lung function greater than 10% below baseline. Subject is admitted to hospital for IV antibiotic treatment or subject is placed on Home IV antibiotics for treatment of exacerbation. <br> Indeterminate = unable to determine clinical status. Consult physician to determine clinical status. | 1:  Clinically Stable <br> 2:  APE Outpatient <br> 3:  APE IV Antibiotics <br> 4:  Indeterminate  |
| start_date_of_iv_antibiotics | IV Antibiotics Start Date | yyyy-mm-dd |
| iv_antiobiotics_end_date | IV Antibiotics End Date | yyyy-mm-dd |
| microbiology_performed_on | Microbiology performed on day of Collection |  0:  No <br> 1:  Yes|
| recent_sputum_micro_mssa | Sputum Microbiology MSSA | 0:  False <br> 1:  True  |
| recent_sputum_micro_mrsa | Sputum Microbiology MRSA | 0:  False <br> 1:  True  |
| recent_sputum_micro_pseudomonas_aeruginosa | Sputum Microbiology Pseudomonas aeruginosa | 0:  False <br> 1:  True  |
| recent_sputum_micro_aspergillus_fumigatus | Sputum Microbiology Aspergillus fumigatus | 0:  False <br> 1:  True  |
| recent_sputum_micro_stenotrophomonas_maltophilia | Sputum Microbiology Stenotrophomonas maltophilia | 0:  False <br> 1:  True  |
| recent_sputum_micro_mycobacterium_abcessus | Sputum Microbiology Mycobacterium abcessus | 0:  False <br> 1:  True  |
| recent_sputum_micro_mycobacterium_avium_complex | Sputum Microbiology Mycobacterium avium complex | 0:  False <br> 1:  True  |
| recent_sputum_micro_normal_flora | Sputum Microbiology Normal Flora | 0:  False <br> 1:  True  |
| recent_sputum_micro_other | Other Sputum Microbiology | 0:  False <br> 1:  True  |
| microbiology_if_other | If other microbiology, specify |  |
| crf_comments | Comments? |  |
| crf_complete | Complete? | 0: Incomplete <br> 1: Unverified <br> 2: Complete|




#### <span id="table_4">4. Bacterial Isolates</span>
| Variable Name | Details | Values |
| :---- | :---- | :---- |
| cfbr_id | CF-BR number of patient |  |
| isolate_id | Identification of Isolates | 1:  Pseudomonas aeruginosa <br> 2:  Stenotrophomonas maltophilia <br>3:  MSSA <br>4:  MRSA <br>5:  Achromobacter xylosoxidans <br>6:  Burkholderia cepacia complex <br>7:  Haemophilus influenzae <br>8:  Aspergillus fumigatus <br>9:  Mycobacterium abscessus (MAB) <br>10: Mycobacterium avium complex (MAC) <br>11: Other|
lab_distributing_isolate |  Lab Distributing Isolate | 1: Clinical lab <br> 2: Investigator lab | 
investigator_lab | Investigator Lab | 1: Steve Diggle <br> 2: Joanna Goldberg <br> 3: Marvin Whiteley <br> 4: Sam Brown <br> 5: Sheyda Azimi <br> 6: Paul Turner |
variant_id | Variant ID | 
| identification_of_pseudomo | Pseudomonas aeruginosa Phenotype | 1:  mucoid <br> 2:  non-mucoid |
| muc_pa_amikacin | Mucoid Pseudomonas aeruginosa susceptibility Amikacin |  1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested|
| nonmuc_pa_amikacin | Non-mucoid Pseudomonas aeruginosa susceptibility Amikacin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| achro_xylo_amikacin | Achromobacter xylosoxidans susceptibility Amikacin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_amikacin | Mycobacterium abscessus susceptibility Amikacin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mac_amikacin | Mycobacterium avium complex (MAC) Susceptibility Amikacin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| muc_pa_aztreonam | Mucoid Pseudomonas aeruginosa susceptibility Aztreonam | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| nonmuc_pa_aztreonam | Non-mucoid Pseudomonas aeruginosa susceptibility Aztreonam | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| achro_xylo_aztreonam | Achromobacter xylosoxidans Susceptibility Aztreonam | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| muc_pa_cefepime | Mucoid Pseudomonas aeruginosa susceptibility Cefepime |  1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested|
| achro_xylo_cefepime | Achromobacter xylosoxidans Cefepime | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| nonmuc_pa_cefepime | Non-mucoid Pseudomonas aeruginosa susceptibility Cefepime | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_cefepime | Mycobacterium abscessus Susceptibility Cefepime | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| muc_pa_ceftazidime | Mucoid Pseudomonas aeruginosa susceptibility Ceftazidime | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| nonmuc_pa_ceftazidime | Non-mucoid Pseudomonas aeruginosa susceptibility Ceftazidime | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| steno_ceftazidime | Stenotrophomonas maltophilia Susceptibility Ceftazidime | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| achro_xylo_ceftazidime | Achromobacter xylosoxidans Susceptibility eftazidime | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| burk_cep_ceftazidime | Burkholderia cepacia complex Susceptibility Ceftazidime | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| muc_pa_colistin | Mucoid Pseudomonas aeruginosa susceptibility Colistin |1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested  |
| nonmuc_pa_colistin | Non-mucoid Pseudomonas aeruginosa susceptibility Colistin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| muc_pa_gentamicin | Mucoid Pseudomonas aeruginosa susceptibility Gentamicin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| nonmuc_pa_gentamicin | Non-mucoid Pseudomonas aeruginosa susceptibility Gentamicin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| achro_xylo_gentamicin | Achromobacter xylosoxidans Susceptibility Gentamicin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_gentamicin | Mycobacterium abscessus Susceptibility Gentamicin |  1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested|
| muc_pa_imipenem | Mucoid Pseudomonas aeruginosa susceptibility Imipenem |  1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested|
| nonmuc_pa_imipenem | Non-mucoid Pseudomonas aeruginosa susceptibility Imipenem | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_imipenem | Mycobacterium abscessus Susceptibility Imipenem | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| muc_pa_levofloxacin | Mucoid Pseudomonas aeruginosa susceptibility Levofloxacin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| nonmuc_pa_levofloxacin | Non-mucoid Pseudomonas aeruginosa susceptibility Levofloxacin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| steno_levofloxacin | Stenotrophomonas maltophilia Susceptibility Levofloxacin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| achro_xylo_levofloxacin | Achromobacter xylosoxidans Susceptibility Levofloxacin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| burk_cep_levofloxacin | Burkholderia cepacia complex Susceptibility Levofloxacin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| muc_pa_meropenem | Mucoid Pseudomonas aeruginosa susceptibility Meropenem | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| nonmuc_pa_meropenem | Non-mucoid Pseudomonas aeruginosa susceptibility Meropenem |1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| achro_xylo_meropenem | Achromobacter xylosoxidans Susceptibility Meropenem |  1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested|
| burk_cep_meropenem | Burkholderia cepacia complex Susceptibility Meropenem | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| muc_pa_piper_tazobac | Mucoid Pseudomonas aeruginosa susceptibility Tazobac | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| nonmuc_pa_piper_tazobac | Non-mucoid Pseudomonas aeruginosa susceptibility Tazobac | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| achro_xylo_piper_tazobac | Achromobacter xylosoxidans Susceptibility Tazobac | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| muc_pa_tobramycin | Mucoid Pseudomonas aeruginosa susceptibility Tobramycin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| nonmuc_pa_tobramycin | Non-mucoid Pseudomonas aeruginosa susceptibility Tobramycin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| achro_xylo_tobramycin | Achromobacter xylosoxidans Susceptibility Tobramycin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| sa_clindamycin | Staphylococcus aureas Susceptibility Clindamycin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| sa_erythromycin | Staphylococcus aureas Susceptibility Erythromycin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| sa_linezolid | Staphylococcus aureas Susceptibility Linezolid | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_linezolid | Mycobacterium abscessus Susceptibility Linezolid | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mac_linezolid | Mycobacterium avium complex (MAC) Susceptibility Linezolid | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| sa_oxacillin | Staphylococcus aureas Susceptibility Oxacillin| 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| sa_tetracycline | Staphylococcus aureas Susceptibility Tetracycline | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| sa_trimethoprim_sulfa | Staphylococcus aureas Susceptibility Sulfa | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| steno_trimethoprim_sulfa | Stenotrophomonas maltophilia Susceptibility Sulfa | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| burk_cep_trimetho_sulfa | Burkholderia cepacia complex Susceptibility Sulfa | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_trimetho_sulfa | Mycobacterium abscessus Susceptibility Sulfa | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| sa_vancomycin | Staphylococcus aureas Susceptibility Vancomycin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| achro_xylo_ticar_clavula | Achromobacter xylosoxidans Susceptibility Clavula | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| steno_minocycline | Stenotrophomonas maltophilia Susceptibility Minocycline | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| burk_cep_minocycline | Burkholderia cepacia complex Susceptibility Minocycline | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_minocycline | Mycobacterium abscessus Susceptibility Minocycline | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| burk_cep_tigecycline | Burkholderia cepacia complex Susceptibility Tigecycline | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_tigecycline | Mycobacterium abscessus Susceptibility Tigecycline | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_amoxicillin_clavula | Mycobacterium abscessus Susceptibility Clavula | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_azithromycin | Mycobacterium abscessus Susceptibility Azithromycin |1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested  |
| mab_cefoxitin | Mycobacterium abscessus Susceptibility Cefoxitin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| muc_pa_ciprofloxacin | Mucoid Pseudomonas aeruginosa susceptibility Ciprofloxacin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| nonmuc_pa_ciprofloxacin | Non-mucoid Pseudomonas aeruginosa susceptibility Ciprofloxacin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_ciprofloxacin | Mycobacterium abscessus Susceptibility Ciprofloxacin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mac_ciprofloxacin | Mycobacterium avium complex (MAC) Susceptibility Ciprofloxacin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_clarithromycin | Mycobacterium abscessus Susceptibility Clarithromycin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mac_clarithromycin | Mycobacterium avium complex (MAC) Susceptibility Clarithromycin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_clofazamine | Mycobacterium abscessus Susceptibility Clofazamine |1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested  |
| mac_clofazamine | Mycobacterium avium complex (MAC) Susceptibility Clofazamine | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_doxycycline | Mycobacterium abscessus Susceptibility Doxycycline | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_kanamycin | Mycobacterium abscessus Susceptibility Kanamycin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_moxifloxacin | Mycobacterium abscessus Susceptibility Moxifloxacin |1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested  |
| mac_moxifloxacin | Mycobacterium avium complex (MAC) Susceptibility Moxifloxacin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mac_ethambutol | Mycobacterium avium complex (MAC) Susceptibility Ethambutol | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mac_ethambutol_combo | Mycobacterium avium complex (MAC) Susceptibility Ethambutol combo| 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mac_rifabutin | Mycobacterium avium complex (MAC) Susceptibility Rifabutin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mac_rifampin | Mycobacterium avium complex (MAC) Susceptibility Rifabutin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mac_rifampin_combo | Mycobacterium avium complex (MAC) Susceptibility Rifabutin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mac_streptomycin | Mycobacterium avium complex (MAC) Susceptibility Streptomycin | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_cefotaxime | Mycobacterium abscessus Susceptibility Cefotaxime | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| achro_xylo_ceftriaxone | Achromobacter xylosoxidans Susceptibility Ceftriaxone | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| mab_ceftriaxone | Mycobacterium abscessus Susceptibility Ceftriaxone | 1:  Susceptible <br>2:  Intermediate <br>3:  Resistant <br>4:  Not Tested |
| isolate_id_other | If other, please type the name of the isolate: |  |
| was_susceptibility_for_mac | Was susceptibility for MAC performed? | 1:  Yes <br> 2:  No <br> |
| beta_lactamase | Beta Lactamase | 1:  Positive <br>2:  Negative <br> |
| microorganisms | Microorganisms | 1:  Single Isolate <br> 2:  Co-cultured <br> |
| microorganisms_mssa | MSSA | 0:  False <br> 1:  True  |
| microorganisms_mrsa | MRSA | 0:  False <br> 1:  True  |
| microorganisms_pseudomonas_aeruginosa | Pseudomonas aeruginosa | 0:  False <br> 1:  True  |
| microorganisms_stenotrophomonas | Stenotrophomonas | 0:  False <br> 1:  True  |
| microorganisms_aspergillus | Aspergillus | 0:  False <br> 1:  True  |
| microorganisms_mycobacterium_abcessus | Mycobacterium abcessus | 0:  False <br> 1:  True  |
| microorganisms_mycobacterium_avium_complex_mac | Mycobacterium avium complex MAC | 0:  False <br> 1:  True  |
| microorganisms_achromobacter_xylosoxidans | Achromobacter xylosoxidans |0:  False <br> 1:  True   |
| microorganisms_burkholderia_cepaciacomplex | Burkholderia cepaciacomplex | 0:  False <br> 1:  True  |
| microorganisms_haemophilus_influenzae | Haemophilus influenzae | 0:  False <br> 1:  True  |
| microorganisms_other | Other | 0:  False <br> 1:  True  |
| other_organism | Other Organism | |
| pseudomonas_aeruginosa_co_mucoid | Pseudomonas aeruginosa co-culture Phenotype:mucoid | 0:  False <br> 1:  True  |
| pseudomonas_aeruginosa_co_non_mucoid | Pseudomonas aeruginosa co-culture Phenotype:non-mucoid | 0:  False <br> 1:  True  |
| pseudomonas_aeruginosa_co_unknown | Pseudomonas aeruginosa co-culture Phenotype:unknown | 0:  False <br> 1:  True  |
| bacsample_type | Sample Type | 1:  Sputum <br>2:  Throat Culture <br>3:  BAL |
| date_specimen_obtained | Date Collected from Subject |yyyy-mm-dd  |
| date_culture_finalized | Date Culture Finalized | yyyy-mm-dd  |
| date_isolate_collected | Date Isolate Collected | yyyy-mm-dd  |
| clinical_status | Clinical Status | 1:  Clinically Stable <br>2:  APE Outpatient <br>3:  APE IV Antibiotics <br>4:  Indeterminate |
| freezer | Freezer Location | 1: Emory Children s Center (ECC)<br>2:  Hiller Lab at Center for Advanced Pediatrics(CAP) <br>3:  Chantilly Lab (NDH)  |
| aliquot_id | Aliquot ID |  |
| isolate_box_number | Box |  |
| isolate_well_location | Well Location |  |
| aminoglycoside_rx | Aminoglycoside Prescribed? | 1: Yes <br> 2: No <br> |
| specific_aminoglycoside | Aminoglycosides | 1: Amikacin <br> 2: Gentamicin <br> 3: Streptomycin <br> 4: Tobramycin |
| aminoglycoside_route_intravenous | Aminoglycoside Administration Route: Intravenous? | 0: False <br> 1: True |
| aminoglycoside_route_oral | Aminoglycoside Administration Route: Oral? | 0: False <br> 1: True |
| aminoglycoside_route_inhaled | Aminoglycoside Administration Route: Inhaled? | 0: False <br> 1: True |
| aminoglycoside_start_date | Aminoglycoside Start Date | yyyy-mm-dd |
| aminoglycoside_end_date | Aminoglycoside End Date | yyyy-mm-dd |
| antifungal_rx | Antifungal Prescribed? | 1: Yes <br> 2: No <br> |
| specific_antifungal | Antifungals | 1: Amphotericin <br> 2: Fluconazole <br> 3: Voriconazole |
| antifungal_route_intravenous | Antifungal Administration Route: Intravenous? | 0: False <br> 1: True |
| antifungal_route_oral | Antifungal Administration Route: Oral? | 0: False <br> 1: True |
| antifungal_route_inhaled | Antifungal Administration Route: Inhaled? | 0: False <br> 1: True |
| antifungal_start_date | Antifungal Start Date | yyyy-mm-dd |
| antifungal_end_date | Antifungal End Date | yyyy-mm-dd |
| carbapenem_rx | Carbapenem Prescribed? | 1: Yes <br> 2: No <br> |
| specific_carbapenem | Carbapenems | 1: Imipenem + Cylastatine (Primaxin) <br> 2: Meropenem |
| carbapenem_route_intravenous | Carbapenem Administration Route: Intravenous? | 0: False <br> 1: True |
| carbapenem_route_oral | Carbapenem Administration Route: Oral? | 0: False <br> 1: True |
| carbapenem_route_inhaled | Carbapenem Administration Route: Inhaled? | 0: False <br> 1: True |
| carbapenem_start_date | Carbapenem Start Date | yyyy-mm-dd |
| carbapenem_end_date | Carbapenem End Date | yyyy-mm-dd |
| cephalosporin_rx | Cephalosporin Prescribed? | 1: Yes <br> 2: No <br> |
| specific_cephalosporin | Cephalosporins | 1: Cefaclor <br> 2: Cefazolin <br> 3: Cefdinir <br> 4: Cefepime <br> 5: Cefixime <br> 6: Cefotaxime <br> 7: Cefoxitin <br> 8: Cefprozil (Cefzil) <br> 9: Ceftaroline <br> 10: Ceftazidime <br> 11: Ceftizoxime <br> 12: Ceftriaxone <br> 13: Cefuroxime <br> 14: Cefphalexine (Keflex) |
| cephalosporin_route_intravenous | Cephalosporin Administration Route: Intravenous? | 0: False <br> 1: True |
| cephalosporin_route_oral | Cephalosporin Administration Route: Oral? | 0: False <br> 1: True |
| cephalosporin_route_inhaled | Cephalosporin Administration Route: Inhaled? | 0: False <br> 1: True |
| cephalosporin_start_date | Cephalosporin Start Date | yyyy-mm-dd |
| cephalosporin_end_date | Cephalosporin End Date | yyyy-mm-dd |
| fluoroquinolone_rx | Fluoroquinolone Prescribed? | 1: Yes <br> 2: No <br> |
| specific_fluoroquinolone | Fluoroquinolones | 1: Ciprofloxacin <br> 2: Levofloxacin <br> 3: Ofloxacin <br> 4: Moxifloxacin |
| fluoroquinolone_route_intravenous | Fluoroquinolone Administration Route: Intravenous? | 0: False <br> 1: True |
| fluoroquinolone_route_oral | Fluoroquinolone Administration Route: Oral? | 0: False <br> 1: True |
| fluoroquinolone_route_inhaled | Fluoroquinolone Administration Route: Inhaled? | 0: False <br> 1: True |
| fluoroquinolone_start_date | Fluoroquinolone Start Date | yyyy-mm-dd |
| fluoroquinolone_end_date | Fluoroquinolone End Date | yyyy-mm-dd |
| lincosamide_rx | Lincosamide Prescribed? | 1: Yes <br> 2: No <br> |
| specific_lincosamide | Lincosamides | 1: Clindamycin <br> 2: Lincomycin |
| lincosamide_route_intravenous | Lincosamide Administration Route: Intravenous? | 0: False <br> 1: True |
| lincosamide_route_oral | Lincosamide Administration Route: Oral? | 0: False <br> 1: True |
| lincosamide_route_inhaled | Lincosamide Administration Route: Inhaled? | 0: False <br> 1: True |
| lincosamide_start_date | Lincosamide Start Date | yyyy-mm-dd |
| lincosamide_end_date | Lincosamide End Date | yyyy-mm-dd |
| macrolide_rx | Macrolide Prescribed? | 1: Yes <br> 2: No <br> |
| specific_macrolide | Macrolides | 1: Azithromycin <br> 2: Clarithromycin <br> 3: Erythromycin |
| macrolide_route_intravenous | Macrolide Administration Route: Intravenous? | 0: False <br> 1: True |
| macrolide_route_oral | Macrolide Administration Route: Oral? | 0: False <br> 1: True |
| macrolide_route_inhaled | Macrolide Administration Route: Inhaled? | 0: False <br> 1: True |
| macrolide_start_date | Macrolide Start Date | yyyy-mm-dd |
| macrolide_end_date | Macrolide End Date | yyyy-mm-dd |
| penicillin_rx | Penicillin Prescribed? | 1: Yes <br> 2: No <br> |
| specific_penicillin | Penicillins | 1: Amoxicillin, Amoxicillin + Clavulanic acid (Augmentin) <br> 2: Ampicillin <br> 3: Carbenicillin <br> 4: Dicloxacillin <br> 5: Nafcillin <br> 6: Oxacillin <br> 7: Piperacillin <br> 8: Piperacillin + Tazobactam (Zosyn) <br> 9: Ticarcillin |
| penicillin_route_intravenous | Penicillin Administration Route: Intravenous? | 0: False <br> 1: True |
| penicillin_route_oral | Penicillin Administration Route: Oral? | 0: False <br> 1: True |
| penicillin_route_inhaled | Penicillin Administration Route: Inhaled? | 0: False <br> 1: True |
| penicillin_start_date | Penicillin Start Date | yyyy-mm-dd |
| penicillin_end_date | Penicillin End Date | yyyy-mm-dd |
| tetracyclin_rx | Tetracyclin Prescribed? | 1: Yes <br> 2: No <br> |
| specific_tetracyclin | Tetracyclins | 1: Doxycycline <br> 2: Minocycline <br> 3: Tetracyclin <br> 4: Tigecyclin |
| tetracyclin_route_intravenous | Tetracyclin Administration Route: Intravenous? | 0: False <br> 1: True |
| tetracyclin_route_oral | Tetracyclin Administration Route: Oral? | 0: False <br> 1: True |
| tetracyclin_route_inhaled | Tetracyclin Administration Route: Inhaled? | 0: False <br> 1: True |
| tetracyclin_start_date | Tetracyclin Start Date | yyyy-mm-dd |
| tetracyclin_end_date | Tetracyclin End Date | yyyy-mm-dd |
| aztreonam_rx | Aztreonam Prescribed? | 1: Yes <br> 2: No <br> |
| aztreonam_route_intravenous | Aztreonam Administration Route: Intravenous? | 0: False <br> 1: True |
| aztreonam_route_oral | Aztreonam Administration Route: Oral? | 0: False <br> 1: True |
| aztreonam_route_inhaled | Aztreonam Administration Route: Inhaled? | 0: False <br> 1: True |
| aztreonam_start_date | Aztreonam Start Date | yyyy-mm-dd |
| aztreonam_end_date | Aztreonam End Date | yyyy-mm-dd |
| ceftaz_avibact_rx | Ceftazidime/Avibactam Prescribed? | 1: Yes <br> 2: No <br> |
| ceftaz_avibact_route_intravenous | Ceftazidime/Avibactam Administration Route: Intravenous? | 0: False <br> 1: True |
| ceftaz_avibact_route_oral | Ceftazidime/Avibactam Administration Route: Oral? | 0: False <br> 1: True |
| ceftaz_avibact_route_inhaled | Ceftazidime/Avibactam Administration Route: Inhaled? | 0: False <br> 1: True |
| ceftaz_avibact_start_date | Ceftazidime/Avibactam Start Date | yyyy-mm-dd |
| ceftaz_avibact_end_date | Ceftazidime/Avibactam End Date | yyyy-mm-dd |
| chloramphenicol_rx | Chloramphenicol Prescribed? | 1: Yes <br> 2: No <br> |
| chloramphenicol_route_intravenous | Chloramphenicol Administration Route: Intravenous? | 0: False <br> 1: True |
| chloramphenicol_route_oral | Chloramphenicol Administration Route: Oral? | 0: False <br> 1: True |
| chloramphenicol_route_inhaled | Chloramphenicol Administration Route: Inhaled? | 0: False <br> 1: True |
| chloramphenicol_start_date | Chloramphenicol Start Date | yyyy-mm-dd |
| chloramphenicol_end_date | Chloramphenicol End Date | yyyy-mm-dd |
| colistin_rx | Colistin Prescribed? | 1: Yes <br> 2: No <br> |
| colistin_route_intravenous | Colistin Administration Route: Intravenous? | 0: False <br> 1: True |
| colistin_route_oral | Colistin Administration Route: Oral? | 0: False <br> 1: True |
| colistin_route_inhaled | Colistin Administration Route: Inhaled? | 0: False <br> 1: True |
| colistin_start_date | Colistin Start Date | yyyy-mm-dd |
| colistin_end_date | Colistin End Date | yyyy-mm-dd |
| ethambutol_rx | Ethambutol Prescribed? | 1: Yes <br> 2: No <br> |
| ethambutol_route_intravenous | Ethambutol Administration Route: Intravenous? | 0: False <br> 1: True |
| ethambutol_route_oral | Ethambutol Administration Route: Oral? | 0: False <br> 1: True |
| ethambutol_route_inhaled | Ethambutol Administration Route: Inhaled? | 0: False <br> 1: True |
| ethambutol_start_date | Ethambutol Start Date | yyyy-mm-dd |
| ethambutol_end_date | Ethambutol End Date | yyyy-mm-dd |
| isoniazid_rx | Isoniazid Prescribed? | 1: Yes <br> 2: No <br> |
| isoniazid_route_intravenous | Isoniazid Administration Route: Intravenous? | 0: False <br> 1: True |
| isoniazid_route_oral | Isoniazid Administration Route: Oral? | 0: False <br> 1: True |
| isoniazid_route_inhaled | Isoniazid Administration Route: Inhaled? | 0: False <br> 1: True |
| isoniazid_start_date | Isoniazid Start Date | yyyy-mm-dd |
| isoniazid_end_date | Isoniazid End Date | yyyy-mm-dd |
| linezolid_rx | Linezolid Prescribed? | 1: Yes <br> 2: No <br> |
| linezolid_route_intravenous | Linezolid Administration Route: Intravenous? | 0: False <br> 1: True |
| linezolid_route_oral | Linezolid Administration Route: Oral? | 0: False <br> 1: True |
| linezolid_route_inhaled | Linezolid Administration Route: Inhaled? | 0: False <br> 1: True |
| linezolid_start_date | Linezolid Start Date | yyyy-mm-dd |
| linezolid_end_date | Linezolid End Date | yyyy-mm-dd |
| polymyxin_b_rx | Polymyxin B Prescribed? | 1: Yes <br> 2: No <br> |
| polymyxin_b_route_intravenous | Polymyxin B Administration Route: Intravenous? | 0: False <br> 1: True |
| polymyxin_b_route_oral | Polymyxin B Administration Route: Oral? | 0: False <br> 1: True |
| polymyxin_b_route_inhaled | Polymyxin B Administration Route: Inhaled? | 0: False <br> 1: True |
| polymyxin_b_start_date | Polymyxin B Start Date | yyyy-mm-dd |
| polymyxin_b_end_date | Polymyxin B End Date | yyyy-mm-dd |
| rifabutin_rx | Rifabutin Prescribed? | 1: Yes <br> 2: No <br> |
| rifabutin_route_intravenous | Rifabutin Administration Route: Intravenous? | 0: False <br> 1: True |
| rifabutin_route_oral | Rifabutin Administration Route: Oral? | 0: False <br> 1: True |
| rifabutin_route_inhaled | Rifabutin Administration Route: Inhaled? | 0: False <br> 1: True |
| rifabutin_start_date | Rifabutin Start Date | yyyy-mm-dd |
| rifabutin_end_date | Rifabutin End Date | yyyy-mm-dd |
| rifampin_rx | Rifampin Prescribed? | 1: Yes <br> 2: No <br> |
| rifampin_route_intravenous | Rifampin Administration Route: Intravenous? | 0: False <br> 1: True |
| rifampin_route_oral | Rifampin Administration Route: Oral? | 0: False <br> 1: True |
| rifampin_route_inhaled | Rifampin Administration Route: Inhaled? | 0: False <br> 1: True |
| rifampin_start_date | Rifampin Start Date | yyyy-mm-dd |
| rifampin_end_date | Rifampin End Date | yyyy-mm-dd |
| bactrim_rx | Trimethoprim + Sulfamethoxazole (Bactrim) Prescribed? | 1: Yes <br> 2: No <br> |
| bactrim_route_intravenous | Bactrim Administration Route: Intravenous? | 0: False <br> 1: True |
| bactrim_route_oral | Trimethoprim + Sulfamethoxazole (Bactrim) Administration Route: Oral? | 0: False <br> 1: True |
| bactrim_route_inhaled | Trimethoprim + Sulfamethoxazole (Bactrim) Administration Route: Inhaled? | 0: False <br> 1: True |
| bactrim_start_date | Trimethoprim + Sulfamethoxazole (Bactrim) Start Date | yyyy-mm-dd |
| bactrim_end_date | Trimethoprim + Sulfamethoxazole (Bactrim) End Date | yyyy-mm-dd |
| vancomycin_rx | Vancomycin Prescribed? | 1: Yes <br> 2: No <br> |
| vancomycin_route_intravenous | Vancomycin Administration Route: Intravenous? | 0: False <br> 1: True |
| vancomycin_route_oral | Vancomycin Administration Route: Oral? | 0: False <br> 1: True |
| vancomycin_route_inhaled | Vancomycin Administration Route: Inhaled? | 0: False <br> 1: True |
| vancomycin_start_date | Vancomycin Start Date | yyyy-mm-dd |
| vancomycin_end_date | Vancomycin End Date | yyyy-mm-dd |
| notes | Notes |  |
| bacterial_isolates_complete | Complete? | 0:  Incomplete <br> 1:  Unverified <br> 2:  Complete <br> |

#### <span id="table_5">5. Glucose Status and OGTT Results</span>
| Variable Name | Details | Values |
| :---- | :---- | :---- |
| cfbr_id | CF-BR number of patient |  |
| conversion_to_cfrd | Conversion to CFRD | 0:  No <br> 1:  Yes|
| conversion_date | Conversion Date | yyyy-mm-dd |
| type_of_ogtt | OGTT Type | 1:  Clinical <br> 1:  Research |
| how_many_time_points | How many time points? | 1:  2 <br> 2:  4 <br> 3:  8 <br> |
| clin_ogtt_date | Date of Clinical OGTT | yyyy-mm-dd |
|ogtt_glu_base_clin | Fasting Glucose (mg/dL) |  |
|ogtt_glu_120_clin | 2 Hour Glucose (mg/dL) |  |
|alternate_study_id | ALTERNATE STUDY ID |  |
|date_of_research_ogtt | Date of research | yyyy-mm-dd |
|ogtt_glu_minus_30 | Timepoint -30min (Baseline) |  |
|ogtt_ins_minus_30 | Insulin (μU/mL) |  |
|ogtt_cpep_minus_30 | C-peptide (ng/mL) |  |
|ogtt_glu_minus_15 | Glucose (mg/dL) |  |
|ogtt_ins_minus_15 | Timepoint -15min (Baseline) |  |
|ogtt_cpep_minus_15 | C-peptide (ng/mL) |  |
|ogtt_glu_base_res | Glucose (mg/dL) |  |
|ogtt_ins_base | Insulin (μU/mL) |  |
|ogtt_cpep_base | C-peptide (ng/mL) |  |
|ogtt_glu_10 | Glucose (mg/dL) |  |
|ogtt_ins_10 | Insulin (μU/mL) |  |
|ogtt_cpep_10 | C-peptide (ng/mL) |  |
|ogtt_glu_20 | Glucose (mg/dL) |  |
|ogtt_ins_20 | Insulin (μU/mL) |  |
|ogtt_cpep_20 | C-peptide (ng/mL) |  |
|ogtt_glu_30 | Glucose (mg/dL) |  |
|ogtt_ins_30 | Insulin (μU/mL) |  |
|ogtt_cpep_30 | C-peptide (ng/mL) |  |
|ogtt_glu_60 | Glucose (mg/dL) |  |
|ogtt_ins_60 | Insulin (μU/mL) |  |
|ogtt_cpep_60 | C-peptide (ng/mL) |  |
|ogtt_glu_90 | Glucose (mg/dL) |  |
|ogtt_ins_90 | Insulin (μU/mL) |  |
|ogtt_cpep_90 | C-peptide (ng/mL) |  |
|ogtt_glu_120 | Glucose (mg/dL) |  |
|ogtt_ins_120 | Insulin (μU/mL) |  |
|ogtt_cpep_120 | C-peptide (ng/mL) |  |
|ogtt_comments | comments |  |
|ogtt_complete | Complete? | 0:  Incomplete <br> 1:  Unverified <br> 2:  Complete <br> |
| homair | HOMA-IR |  |
| wbisi | WBISI (whole-body insulin sensitivity index) |  |
| reverse_fast_insulin_pmol_l | 1_insulin (pM-1) |  |
| igi_i | Insulinogenic Index (µU/mmol) |  |
| homab | HOMA-β% |  |
| isc | Insulin secretion (pmol/mmol) |  |
| odi_mat | Oral Disposition Index Matsuda  |  |
| odi_mer | Oral Disposition Index Merjaneh (mM-1) |  |
| auc_ins | Area under the curve for insulin (pmol*min/L)  |  |
| auc_glu | Area under the curve for glucose (mmol*min/L) |  |
| auc_cpep | Area under the curve for c-peptide (nmol*min/L) |  |
| iauc_ins | Incremental area under the curve for insulin  (pmol*min/L) |  |
| iauc_glu | Incremental area under the curve for glucose (mmol*min/L) |  |
| iauc_cpep | Incremental area under the curve for c-peptide (nmol*min/L) |  |


#### <span id="table_6">5. CGM CRF</span>
| Variable Name | Details | Values |
| :---- | :---- | :---- |
| cfbr_id | CF-BR number of patient |  |
| cgm_alt_study_id | Alternate Study ID |  |
| cgm_start_date | CGM Start Date | yyyy-mm-dd |
| cgm_end_date | CGM Removal Date | yyyy-mm-dd |
| no_of_days_cgm_worn | Number of Days with 24 hours of Data | 0: 0 <br> 1: 1 <br> 2: 2 <br> 3: 3 <br> 4: 4 <br> 5: 5 <br> 6: 6 <br> 7: 7 <br> 8: 8 <br> 9: 9 <br> 10: 10 <br> |
| was_cgm_placed_during_ogtt | Placed during OGTT? | 1:  Yes <br> 0:  No <br> |
| cgm_date_of_ogtt | Date of OGTT |  |
| cgm_comments | comments |  |
| cgm_crf_complete | Complete? | 0:  Incomplete <br> 1:  Unverified <br> 2:  Complete <br> |
