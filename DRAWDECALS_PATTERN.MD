client.dll

Decals Translucent to Resolved Depth
D_MSAA_DEPTH_BUFFER

_BYTE *__fastcall sub_1810ECF80(__int64 a1, __int64 **a2, char a3, char a4)
{
  char v7; // bl
  _BYTE *result; // rax
  char v9; // si
  __int64 v10; // r15
  _BYTE *v11; // rax
  char v12; // r14
  _BYTE *v13; // rax
  __int64 *v14; // rcx
  __int64 *v15; // rdx
  __int64 *v16; // rdi
  __int64 v17; // rdx
  __int64 (__fastcall *v18)(__int64 *, const char *, __int64 **, int *); // rbx
  __int64 v19; // rbx
  _BYTE *v20; // rax
  _BYTE *v21; // rax
  __int64 *v22; // rdi
  __int64 v23; // rax
  __int64 (__fastcall *v24)(__int64 *, const char *, __int64 **, int *); // rbx
  __int64 v25; // rbx
  __int64 *v26; // rcx
  __int64 *v27; // rax
  __int64 v28; // r9
  __int64 v29; // rax
  unsigned __int8 v30; // cl
  __int64 v31; // rbx
  int v32; // edi
  __int64 v33; // rax
  __int64 v34; // rsi
  __int64 *v35; // rdx
  char v36; // r8
  unsigned int v37; // eax
  int v38; // eax
  __int64 v39; // r9
  __m128i *v40; // r13
  unsigned int v41; // ecx
  __m128i *v42; // rax
  __int64 v43; // rdx
  unsigned int v44; // ecx
  __m128i v45; // xmm1
  int v46; // r8d
  _QWORD *v47; // rax
  __m128i *v48; // rcx
  unsigned int v49; // r8d
  int v50; // r8d
  int *v51; // r8
  _QWORD *v52; // rbx
  __int64 v53; // rdi
  unsigned __int64 v54; // rax
  int v55; // eax
  unsigned int v56; // eax
  __m128i si128; // xmm1
  __m128i *v58; // rax
  unsigned int v59; // ecx
  int v60; // edx
  _QWORD *v61; // rax
  __m128i *v62; // rcx
  unsigned int v63; // edx
  int v64; // r8d
  int v65; // edx
  int *v66; // rcx
  int v67; // r8d
  _QWORD *v68; // rbx
  __int64 v69; // rcx
  __int64 v70; // rbx
  __m128i v71; // xmm1
  unsigned int v72; // ecx
  __m128i *v73; // rax
  int v74; // edx
  _QWORD *v75; // rax
  __m128i *v76; // rcx
  unsigned int v77; // edx
  int v78; // r8d
  unsigned __int64 v79; // rcx
  int v80; // edx
  int *v81; // rcx
  int v82; // r8d
  _QWORD *v83; // r14
  const char *v84; // rdx
  __int64 v85; // rax
  int v86; // eax
  unsigned int v87; // eax
  unsigned int v88; // ebx
  __int64 v89; // r9
  unsigned __int64 v90; // rdi
  _BYTE *v91; // rax
  _BYTE *v92; // rax
  __int64 *v93; // rdi
  __int64 v94; // rax
  __int64 (__fastcall *v95)(__int64 *, const char *, __int64 **, int *); // rbx
  __int64 v96; // rbx
  __int64 v97; // rax
  unsigned __int64 v98; // rcx
  __int64 *v99; // rbx
  __int64 (__fastcall *v100)(__int64 *, const char *, __int64 **, __int64, int); // rdi
  __int64 v101; // rax
  __int64 v102; // rax
  int v103; // [rsp+20h] [rbp-59h]
  unsigned __int8 v104; // [rsp+30h] [rbp-49h]
  char v105; // [rsp+31h] [rbp-48h] BYREF
  char v106; // [rsp+32h] [rbp-47h]
  __int64 v107; // [rsp+38h] [rbp-41h] BYREF
  __int64 v108; // [rsp+40h] [rbp-39h] BYREF
  int v109; // [rsp+48h] [rbp-31h]
  __int64 v110; // [rsp+50h] [rbp-29h]
  __int64 v111; // [rsp+58h] [rbp-21h]
  int v112; // [rsp+60h] [rbp-19h] BYREF
  int v113; // [rsp+68h] [rbp-11h] BYREF
  int v114; // [rsp+6Ch] [rbp-Dh]
  __int64 v115; // [rsp+70h] [rbp-9h]
  __int64 v116; // [rsp+78h] [rbp-1h] BYREF
  int v117; // [rsp+80h] [rbp+7h] BYREF
  _DWORD v118[2]; // [rsp+88h] [rbp+Fh] BYREF
  __int64 v119; // [rsp+90h] [rbp+17h]
  __int128 v120; // [rsp+98h] [rbp+1Fh] BYREF
  int v121; // [rsp+A8h] [rbp+2Fh]
  unsigned int v122; // [rsp+F8h] [rbp+7Fh] BYREF

  LOBYTE(v122) = a4;
  if ( !a4 || a3 )
  {
    v7 = 0;
    v104 = 0;
  }
  else
  {
    v7 = 1;
    v104 = 1;
    result = (_BYTE *)sub_181814B90(&unk_1823BAD48, 0xFFFFFFFFLL);
    if ( !result )
      result = *(_BYTE **)(qword_1823BAD50 + 8);
    if ( !*result )
      return result;
    result = (_BYTE *)sub_181814B90(&unk_1823BAD38, 0xFFFFFFFFLL);
    if ( !result )
      result = *(_BYTE **)(qword_1823BAD40 + 8);
    if ( !*result )
      return result;
  }
  v9 = *((_BYTE *)a2 + 392);
  v10 = 0LL;
  v111 = -1LL;
  v110 = 0LL;
  if ( !v9 )
    goto LABEL_16;
  v11 = (_BYTE *)sub_181814B90(&unk_1823BB2A8, 0xFFFFFFFFLL);
  if ( !v11 )
    v11 = *(_BYTE **)(qword_1823BB2B0 + 8);
  if ( *v11 )
    v12 = 1;
  else
LABEL_16:
    v12 = 0;
  v106 = *((_BYTE *)a2 + 443);
  v13 = (_BYTE *)sub_181814B90(&unk_1823BAD38, 0xFFFFFFFFLL);
  if ( !v13 )
    v13 = *(_BYTE **)(qword_1823BAD40 + 8);
  if ( *v13 && a4 )
  {
    v14 = *a2;
    v15 = a2[11];
    v120 = 0LL;
    v121 = 13;
    (*(void (__fastcall **)(__int64 *, __int64 *, __int128 *))(*v14 + 328))(v14, v15, &v120);
    if ( v12 && !v7 )
      v111 = (*(__int64 (__fastcall **)(__int64 *, const char *, __int128 *, __int64))(**a2 + 720))(
               *a2,
               "DecalDepthWithTranslucent",
               &v120,
               1LL);
    v16 = *a2;
    v17 = **a2;
    v117 = 0;
    v118[1] = -1073741816;
    v118[0] = 0;
    v18 = *(__int64 (__fastcall **)(__int64 *, const char *, __int64 **, int *))(v17 + 8);
    v119 = 0LL;
    sub_180D9F360(&v117, "Depth");
    v107 = v18(v16, "Decals Translucent Depth", a2 + 2, &v117);
    v19 = v107;
    CBufferString::Purge((CBufferString *)v118, 0);
    if ( v9 && v104 )
    {
      *(_QWORD *)(v107 + 168) = a2[11];
      *(_DWORD *)(v19 + 88) = 0;
      *(_QWORD *)(v19 + 96) = -1LL;
      *(_BYTE *)(v19 + 160) = 0;
      v20 = (_BYTE *)sub_181814B90(&unk_1823BB438, 0xFFFFFFFFLL);
      if ( !v20 )
        v20 = *(_BYTE **)(qword_1823BB440 + 8);
      if ( *v20 )
      {
        v21 = (_BYTE *)sub_181814B90(&unk_1823BB498, 0xFFFFFFFFLL);
        if ( !v21 )
          v21 = *(_BYTE **)(qword_1823BB4A0 + 8);
        if ( *v21 && !v12 )
        {
          v22 = *a2;
          v23 = **a2;
          v114 = -1073741816;
          v24 = *(__int64 (__fastcall **)(__int64 *, const char *, __int64 **, int *))(v23 + 8);
          v112 = 0;
          v113 = 0;
          v115 = 0LL;
          sub_180D9F360(&v112, "Depth");
          v110 = v24(v22, "Decals Translucent to Resolved Depth", a2 + 2, &v112);
          v25 = v110;
          CBufferString::Purge((CBufferString *)&v113, 0);
          v26 = a2[16];
          *(_DWORD *)(v110 + 88) = 0;
          *(_BYTE *)(v25 + 160) = 0;
          v10 = v107;
          *(_QWORD *)(v25 + 168) = v26;
          *(_QWORD *)(v25 + 96) = -1LL;
LABEL_38:
          sub_1810E7840(&v105, v10);
          LOBYTE(v28) = 1;
          LODWORD(v107) = 0;
          v29 = sub_1810E7600(&v105, &v107, v104, v28);
          v30 = v104;
          v31 = v29;
          v32 = v107;
          *(_QWORD *)(v10 + 1680) = v29;
          *(_DWORD *)(v10 + 1740) = v32;
          if ( v104 )
          {
            *(_DWORD *)(v10 + 80) |= 0x200u;
          }
          else if ( v12 )
          {
            *(_DWORD *)(v10 + 80) |= 0x300u;
          }
          v33 = v110;
          if ( v110 )
          {
            sub_1810E7840(&v105, v110);
            v33 = v110;
            v30 = v104;
            *(_QWORD *)(v110 + 1680) = v31;
            *(_DWORD *)(v33 + 1740) = v32;
            if ( v104 )
              *(_DWORD *)(v33 + 80) |= 0x200u;
          }
          if ( v9 && !v12 && v30 && !v33 && v106 )
            sub_1811083E0(a1, a2, 0LL);
          goto LABEL_51;
        }
      }
    }
    else
    {
      v27 = (__int64 *)v111;
      if ( !v12 )
        v27 = a2[16];
      *(_QWORD *)(v107 + 168) = v27;
      *(_DWORD *)(v19 + 88) = 0;
      *(_QWORD *)(v19 + 96) = -1LL;
      *(_BYTE *)(v19 + 160) = 0;
    }
    v10 = v19;
    goto LABEL_38;
  }
LABEL_51:
  v34 = (*(__int64 (__fastcall **)(__int64 *, const char *, __int64 **, __int64 **))(**a2 + 8))(
          *a2,
          "Decals (Static and Dynamic)",
          a2 + 2,
          a2 + 50);
  *(_QWORD *)(v34 + 72) |= 0x400001uLL;
  *(_QWORD *)(v34 + 1168) |= 0x8000uLL;
  v35 = a2[10];
  v36 = *((_BYTE *)a2 + 436);
  *(_QWORD *)(v34 + 168) = a2[11];
  *(_QWORD *)(v34 + 96) = v35;
  *(_BYTE *)(v34 + 160) = v36;
  *(_DWORD *)(v34 + 88) = (__int64 *)((char *)v35 + 1) != 0LL;
  (*(void (__fastcall **)(__int64, __int64))(*(_QWORD *)v34 + 48LL))(v34, v34);
  *(_QWORD *)(v34 + 72) |= 0x12000uLL;
  if ( v104 )
  {
    *(_DWORD *)((char *)&v107 + 2) = 0;
    HIWORD(v107) = 0;
    if ( dword_1822B7DD0 > *(_DWORD *)(*((_QWORD *)NtCurrentTeb()->ThreadLocalStoragePointer + (unsigned int)TlsIndex)
                                     + 152LL) )
    {
      sub_18185DCA8(&dword_1822B7DD0, 152LL);
      if ( dword_1822B7DD0 == -1 )
      {
        qword_1822B7DC8 = 0xFFFF01C01C000303uLL;
        sub_18185DC3C(&dword_1822B7DD0);
      }
    }
    HIBYTE(v107) = HIBYTE(qword_1822B7DC8);
    BYTE1(v107) = 3;
    BYTE6(v107) = 4;
    LOBYTE(v107) = qword_1822B7DC8 & 0xFC | 1;
    WORD1(v107) = 2049;
    WORD2(v107) = WORD2(qword_1822B7DC8) & 0xFE00 | 0x80;
    *(_QWORD *)(v34 + 1680) = (*(__int64 (__fastcall **)(__int64, __int64 *))(*(_QWORD *)qword_182541B48 + 248LL))(
                                qword_182541B48,
                                &v107);
    *(_DWORD *)(v34 + 1740) = 4;
  }
  if ( v12 )
  {
    v37 = sub_18016EA80("D_MSAA_DEPTH_BUFFER", 826366261LL);
    v38 = sub_18016EA80("EPTH_BUFFER", v37);
    v40 = (__m128i *)(v34 + 496);
    v41 = 1540483477 * ((1540483477 * (v38 ^ 0x726566)) ^ ((1540483477 * (v38 ^ 0x726566u)) >> 13));
    v42 = (__m128i *)(v34 + 496);
    v43 = v41 ^ (v41 >> 15);
    v44 = 0;
    v45 = _mm_shuffle_epi32(_mm_cvtsi32_si128(v43), 0);
    while ( 1 )
    {
      v46 = _mm_movemask_ps((__m128)_mm_cmpeq_epi32(v45, *v42));
      if ( v46 )
        break;
      ++v44;
      ++v42;
      if ( v44 >= 3 )
        goto LABEL_58;
    }
    v50 = dword_1820BA5A0[v46] + 4 * v44;
    if ( (unsigned int)v50 < 0xC )
    {
      v51 = &v40[3].m128i_i32[v50];
LABEL_70:
      v52 = (_QWORD *)(v34 + 1128);
      *(_QWORD *)(v34 + 1128) ^= (0x94D049BB133111EBuLL
                                * ((0xBF58476D1CE4E5B9uLL
                                  * ((*v51 | ((unsigned __int64)(unsigned int)v43 << 32)) ^ ((*v51 | ((unsigned __int64)(unsigned int)v43 << 32)) >> 30))) ^ ((0xBF58476D1CE4E5B9uLL * ((*v51 | ((unsigned __int64)(unsigned int)v43 << 32)) ^ ((*v51 | ((unsigned __int64)(unsigned int)v43 << 32)) >> 30))) >> 27))) ^ ((0x94D049BB133111EBuLL * ((0xBF58476D1CE4E5B9uLL * ((*v51 | ((unsigned __int64)(unsigned int)v43 << 32)) ^ ((*v51 | ((unsigned __int64)(unsigned int)v43 << 32)) >> 30))) ^ ((0xBF58476D1CE4E5B9uLL * ((*v51 | ((unsigned __int64)(unsigned int)v43 << 32)) ^ ((*v51 | ((unsigned __int64)(unsigned int)v43 << 32)) >> 30))) >> 27))) >> 31);
      goto LABEL_68;
    }
LABEL_58:
    v47 = *(_QWORD **)(v34 + 600);
    if ( v47 )
    {
      while ( 2 )
      {
        v48 = (__m128i *)(v47 + 2);
        v49 = 0;
        while ( 1 )
        {
          v39 = (unsigned int)_mm_movemask_ps((__m128)_mm_cmpeq_epi32(v45, *v48));
          if ( (_DWORD)v39 )
            break;
          ++v49;
          ++v48;
          if ( v49 >= 3 )
            goto LABEL_66;
        }
        v39 = dword_1820BA5A0[(int)v39] + 4 * v49;
        if ( (unsigned int)v39 < 0xC )
        {
          v51 = (int *)v47 + (int)v39 + 16;
          goto LABEL_70;
        }
LABEL_66:
        v47 = (_QWORD *)*v47;
        if ( v47 )
          continue;
        break;
      }
    }
    v52 = (_QWORD *)(v34 + 1128);
LABEL_68:
    v53 = (unsigned int)v43;
    sub_1801738E0(v34 + 496, v43, 1LL, v39);
    v54 = ((v53 << 32) | 1) ^ (((v53 << 32) | 1uLL) >> 30);
    *v52 ^= (0x94D049BB133111EBuLL * ((0xBF58476D1CE4E5B9uLL * v54) ^ ((0xBF58476D1CE4E5B9uLL * v54) >> 27))) ^ ((0x94D049BB133111EBuLL * ((0xBF58476D1CE4E5B9uLL * v54) ^ ((0xBF58476D1CE4E5B9uLL * v54) >> 27))) >> 31);
    v55 = sub_18016EA80("SceneDepthDecal", 826366249LL);
    v56 = 1540483477
        * ((1540483477 * ((1540483477 * v55) ^ 0xE010DE12)) ^ ((1540483477 * ((1540483477 * v55) ^ 0xE010DE12)) >> 13));
    sub_1811354D0(v34, v56 ^ (v56 >> 15), (unsigned int)a2[11], 1, 1, 0);
  }
  else
  {
    si128 = _mm_load_si128((const __m128i *)&xmmword_181B705F0);
    v40 = (__m128i *)(v34 + 496);
    v58 = (__m128i *)(v34 + 496);
    v59 = 0;
    while ( 1 )
    {
      v60 = _mm_movemask_ps((__m128)_mm_cmpeq_epi32(si128, *v58));
      if ( v60 )
        break;
      ++v59;
      ++v58;
      if ( v59 >= 3 )
        goto LABEL_74;
    }
    v65 = dword_1820BA5A0[v60] + 4 * v59;
    if ( (unsigned int)v65 < 0xC )
    {
      v66 = &v40[3].m128i_i32[v65];
LABEL_97:
      v68 = (_QWORD *)(v34 + 1128);
      v79 = 0xBF58476D1CE4E5B9uLL * ((*v66 | 0xE169A90000000000uLL) ^ ((*v66 | 0xE169A90000000000uLL) >> 30));
      *(_QWORD *)(v34 + 1128) ^= (0x94D049BB133111EBuLL * (v79 ^ (v79 >> 27))) ^ ((0x94D049BB133111EBuLL
                                                                                 * (v79 ^ (v79 >> 27))) >> 31);
      goto LABEL_84;
    }
LABEL_74:
    v61 = *(_QWORD **)(v34 + 600);
    if ( v61 )
    {
      while ( 2 )
      {
        v62 = (__m128i *)(v61 + 2);
        v63 = 0;
        while ( 1 )
        {
          v64 = _mm_movemask_ps((__m128)_mm_cmpeq_epi32(si128, *v62));
          if ( v64 )
            break;
          ++v63;
          ++v62;
          if ( v63 >= 3 )
            goto LABEL_82;
        }
        v67 = dword_1820BA5A0[v64] + 4 * v63;
        if ( (unsigned int)v67 < 0xC )
        {
          v66 = (int *)v61 + v67 + 16;
          goto LABEL_97;
        }
LABEL_82:
        v61 = (_QWORD *)*v61;
        if ( v61 )
          continue;
        break;
      }
    }
    v68 = (_QWORD *)(v34 + 1128);
LABEL_84:
    sub_1801738E0(v34 + 496, 3781798144LL, 0LL, 0x94D049BB133111EBuLL);
    *v68 ^= 0x9BC53ADF2525709uLL;
    if ( a2[16] != (__int64 *)-1LL )
    {
      (*(void (__fastcall **)(_QWORD, __int64 *))(**(_QWORD **)(v34 + 1776) + 352LL))(*(_QWORD *)(v34 + 1776), &v116);
      v69 = *(_QWORD *)(v34 + 1776);
      v105 = 0;
      LODWORD(v107) = -1;
      (*(void (__fastcall **)(__int64, __int64, __int64 *, char *))(*(_QWORD *)v69 + 768LL))(v69, v116, &v107, &v105);
      v108 = (unsigned int)v107 | 0x100000000LL;
      sub_180DA2E80(v34 + 1280, 2666358789LL, v108);
      v108 = v116;
      v109 = -1;
      sub_1801985F0(v34 + 608, 2666358789LL, &v108);
      v108 = v116;
      v109 = 0;
      sub_180D75EF0(v34 + 1816, &v108);
    }
  }
  v70 = v111;
  if ( v111 != -1 )
    sub_1811354D0(v34, -622586092, v111, 1, 1, 0);
  v71 = _mm_load_si128((const __m128i *)&xmmword_181B702F0);
  v72 = 0;
  v73 = v40;
  while ( 1 )
  {
    v74 = _mm_movemask_ps((__m128)_mm_cmpeq_epi32(v71, *v73));
    if ( v74 )
      break;
    ++v72;
    ++v73;
    if ( v72 >= 3 )
      goto LABEL_91;
  }
  v80 = dword_1820BA5A0[v74] + 4 * v72;
  if ( (unsigned int)v80 < 0xC )
  {
    v81 = &v40[3].m128i_i32[v80];
LABEL_124:
    v83 = (_QWORD *)(v34 + 1128);
    v98 = 0xBF58476D1CE4E5B9uLL * ((*v81 | 0x2441584B00000000LL) ^ ((*v81 | 0x2441584B00000000uLL) >> 30));
    *(_QWORD *)(v34 + 1128) ^= (0x94D049BB133111EBuLL * (v98 ^ (v98 >> 27))) ^ ((0x94D049BB133111EBuLL
                                                                               * (v98 ^ (v98 >> 27))) >> 31);
    goto LABEL_103;
  }
LABEL_91:
  v75 = (_QWORD *)v40[6].m128i_i64[1];
  if ( v75 )
  {
    while ( 2 )
    {
      v76 = (__m128i *)(v75 + 2);
      v77 = 0;
      while ( 1 )
      {
        v78 = _mm_movemask_ps((__m128)_mm_cmpeq_epi32(v71, *v76));
        if ( v78 )
          break;
        ++v77;
        ++v76;
        if ( v77 >= 3 )
          goto LABEL_101;
      }
      v82 = dword_1820BA5A0[v78] + 4 * v77;
      if ( (unsigned int)v82 < 0xC )
      {
        v81 = (int *)v75 + v82 + 16;
        goto LABEL_124;
      }
LABEL_101:
      v75 = (_QWORD *)*v75;
      if ( v75 )
        continue;
      break;
    }
  }
  v83 = (_QWORD *)(v34 + 1128);
LABEL_103:
  sub_1801738E0(v40, 608262219LL, v70 != -1, 0x2441584B00000000LL);
  v84 = "Decals on Translucent";
  *v83 ^= (0x94D049BB133111EBuLL
         * ((0xBF58476D1CE4E5B9uLL
           * (((v70 != -1) | 0x2441584B00000000LL) ^ (((v70 != -1) | 0x2441584B00000000uLL) >> 30))) ^ ((0xBF58476D1CE4E5B9uLL * (((v70 != -1) | 0x2441584B00000000LL) ^ (((v70 != -1) | 0x2441584B00000000uLL) >> 30))) >> 27))) ^ ((0x94D049BB133111EBuLL * ((0xBF58476D1CE4E5B9uLL * (((v70 != -1) | 0x2441584B00000000LL) ^ (((v70 != -1) | 0x2441584B00000000uLL) >> 30))) ^ ((0xBF58476D1CE4E5B9uLL * (((v70 != -1) | 0x2441584B00000000LL) ^ (((v70 != -1) | 0x2441584B00000000uLL) >> 30))) >> 27))) >> 31);
  if ( !v104 )
    v84 = "Decals";
  (*(void (__fastcall **)(__int64, const char *))(*(_QWORD *)v34 + 120LL))(v34, v84);
  if ( v10 )
  {
    v108 = v34;
    sub_18110AC80(v10 + 1784, &v108);
  }
  result = (_BYTE *)v110;
  if ( v110 )
  {
    v108 = v34;
    result = (_BYTE *)sub_18110AC80(v110 + 1784, &v108);
  }
  if ( v106 && (_BYTE)v122 )
  {
    v85 = sub_181123350(a2);
    sub_1811361F0(v34, v85);
    v86 = sub_18016EA80("D_MBOIT_PASS2", 826366251LL);
    v87 = 1540483477
        * ((1540483477 * ((1540483477 * v86) ^ 0x110A6E78)) ^ ((1540483477 * ((1540483477 * v86) ^ 0x110A6E78u)) >> 13));
    v88 = v87 ^ (v87 >> 15);
    v122 = v88;
    if ( (unsigned __int8)sub_180BD89C0(v40, &v107, &v122, 0LL) )
      *v83 ^= (0x94D049BB133111EBuLL
             * ((0xBF58476D1CE4E5B9uLL
               * (((int)v107 | ((unsigned __int64)v88 << 32)) ^ (((int)v107 | ((unsigned __int64)v88 << 32)) >> 30))) ^ ((0xBF58476D1CE4E5B9uLL * (((int)v107 | ((unsigned __int64)v88 << 32)) ^ (((int)v107 | ((unsigned __int64)v88 << 32)) >> 30))) >> 27))) ^ ((0x94D049BB133111EBuLL * ((0xBF58476D1CE4E5B9uLL * (((int)v107 | ((unsigned __int64)v88 << 32)) ^ (((int)v107 | ((unsigned __int64)v88 << 32)) >> 30))) ^ ((0xBF58476D1CE4E5B9uLL * (((int)v107 | ((unsigned __int64)v88 << 32)) ^ (((int)v107 | ((unsigned __int64)v88 << 32)) >> 30))) >> 27))) >> 31);
    sub_1801738E0(v40, v88, 1LL, v89);
    v90 = ((unsigned __int64)v88 << 32) | 1;
    result = (_BYTE *)((0x94D049BB133111EBuLL
                      * ((0xBF58476D1CE4E5B9uLL * (v90 ^ (v90 >> 30))) ^ ((0xBF58476D1CE4E5B9uLL * (v90 ^ (v90 >> 30))) >> 27))) ^ *(_QWORD *)(v34 + 1128) ^ ((0x94D049BB133111EBuLL * ((0xBF58476D1CE4E5B9uLL * (v90 ^ (v90 >> 30))) ^ ((0xBF58476D1CE4E5B9uLL * (v90 ^ (v90 >> 30))) >> 27))) >> 31));
    *(_QWORD *)(v34 + 1128) = result;
  }
  if ( v104 && v10 )
  {
    v91 = (_BYTE *)sub_181814B90(&unk_1823BB438, 0xFFFFFFFFLL);
    if ( !v91 )
      v91 = *(_BYTE **)(qword_1823BB440 + 8);
    if ( !*v91 )
      goto LABEL_125;
    v92 = (_BYTE *)sub_181814B90(&unk_1823BB498, 0xFFFFFFFFLL);
    if ( !v92 )
      v92 = *(_BYTE **)(qword_1823BB4A0 + 8);
    if ( *v92 )
    {
      v93 = *a2;
      v94 = **a2;
      v112 = 0;
      v114 = -1073741816;
      v113 = 0;
      v95 = *(__int64 (__fastcall **)(__int64 *, const char *, __int64 **, int *))(v94 + 8);
      v115 = 0LL;
      sub_180D9F360(&v112, "Depth");
      v96 = v95(v93, "Clear Stencil Translucent Decals", a2 + 2, &v112);
      CBufferString::Purge((CBufferString *)&v113, 0);
      *(_QWORD *)(v96 + 168) = a2[11];
      *(_DWORD *)(v96 + 88) = 0;
      *(_QWORD *)(v96 + 96) = -1LL;
      *(_BYTE *)(v96 + 160) = 0;
      sub_1810E7840(&v105, v96);
      v122 = 0;
      v97 = sub_1810E7600(&v105, &v122, v104, 0LL);
      *(_DWORD *)(v96 + 80) |= 0x200u;
      *(_QWORD *)(v96 + 1680) = v97;
      *(_DWORD *)(v96 + 1740) = v122;
      v108 = v34;
      result = (_BYTE *)sub_18110AC80(v96 + 1784, &v108);
    }
    else
    {
LABEL_125:
      v99 = *a2;
      v100 = *(__int64 (__fastcall **)(__int64 *, const char *, __int64 **, __int64, int))(**a2 + 16);
      v101 = sub_180B8F6C0(16LL);
      if ( v101 )
      {
        *(_BYTE *)(v101 + 8) = 4;
        *(_QWORD *)v101 = off_181B6D768;
      }
      LOBYTE(v103) = 1;
      v102 = v100(v99, "Clear Decal Translucent Stencil Bit", a2 + 2, v101, v103);
      *(_QWORD *)(v102 + 168) = *(_QWORD *)(v10 + 168);
      *(_DWORD *)(v102 + 88) = 0;
      *(_QWORD *)(v102 + 96) = -1LL;
      *(_BYTE *)(v102 + 160) = 0;
      *(_QWORD *)(v102 + 1160) = -1LL;
      result = (_BYTE *)sub_18111F8F0(v102, v34);
    }
  }
  if ( v111 != -1 )
    return (_BYTE *)(*(__int64 (__fastcall **)(__int64 *))(**a2 + 744))(*a2);
  return result;
}
