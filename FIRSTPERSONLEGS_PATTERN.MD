first person legs strings - client.dll

FirstpersonLegsPrepass
FirstpersonLegsPass1
CsgoForward
FirstpersonLegsPass2

void __fastcall firstpersonLegs(__int64 *a1, __int64 *a2, __int64 a3, __int64 a4, __int64 a5)
{
  int v6; // eax
  _BYTE *v10; // rax
  __int64 v11; // rax
  float v12; // edi
  __int64 v13; // rax
  __int64 *v14; // rax
  __int64 v15; // rdx
  _OWORD *v16; // rcx
  __int128 v17; // xmm1
  __int128 v18; // xmm0
  __int128 v19; // xmm1
  __int128 v20; // xmm0
  __int128 v21; // xmm1
  __int128 v22; // xmm0
  __int128 v23; // xmm1
  __int128 v24; // xmm1
  float *v25; // rax
  __int64 v26; // rax
  int v27; // r12d
  __int64 (__fastcall *v28)(__int64 *, const char *, _DWORD *, unsigned int *); // r14
  unsigned __int8 *v29; // rdi
  unsigned __int8 *v30; // r8
  int v31; // edx
  __int64 v32; // r9
  unsigned int v33; // eax
  int v34; // ecx
  unsigned int v35; // eax
  unsigned int v36; // ebx
  __int64 v37; // r14
  __int64 v38; // r13
  __int64 v39; // rax
  int v40; // edx
  __int64 v41; // r8
  unsigned int v42; // eax
  int v43; // eax
  unsigned int v44; // ebx
  __int64 v45; // rbx
  __int64 v46; // rax
  __int64 v47; // [rsp+30h] [rbp-D0h] BYREF
  unsigned int v48; // [rsp+40h] [rbp-C0h] BYREF
  int v49; // [rsp+48h] [rbp-B8h] BYREF
  int v50; // [rsp+4Ch] [rbp-B4h]
  __int64 v51; // [rsp+50h] [rbp-B0h]
  __int64 v52; // [rsp+58h] [rbp-A8h] BYREF
  int v53; // [rsp+60h] [rbp-A0h]
  _DWORD v54[10]; // [rsp+68h] [rbp-98h] BYREF
  int v55; // [rsp+90h] [rbp-70h] BYREF
  int v56; // [rsp+94h] [rbp-6Ch]
  _QWORD v57[17]; // [rsp+98h] [rbp-68h] BYREF
  _BYTE v58[32]; // [rsp+120h] [rbp+20h] BYREF
  float v59; // [rsp+140h] [rbp+40h]
  __int64 (__fastcall *v60)(__int64 *, const char *, _DWORD *, unsigned int *); // [rsp+598h] [rbp+498h] BYREF

  v6 = *((_DWORD *)a2 + 9);
  v52 = *(__int64 *)((char *)a2 + 28);
  v53 = v6;
  v10 = (_BYTE *)sub_1818120A0(&unk_1823B93D8, 0xFFFFFFFFLL);
  if ( !v10 )
    v10 = *(_BYTE **)(qword_1823B93E0 + 8);
  if ( !*v10
    || (v11 = sub_1815C12A0(&v52, &v48),
        v12 = *(float *)(v11 + 8),
        v47 = *(_QWORD *)v11,
        sub_1818120A0(&unk_1823B9458, 0xFFFFFFFFLL),
        V_cosf() <= (float)((float)(*(float *)&v47 * 0.0)
                          + (float)((float)(*((float *)&v47 + 1) * 0.0) - (float)(v12 * 1.0)))) )
  {
    v13 = *a1;
    v54[0] = 1;
    (*(void (__fastcall **)(__int64 *, _QWORD, __int64, _DWORD *))(v13 + 24))(a1, 0LL, a3, v54);
    v14 = a2 + 2;
    v15 = 8LL;
    v16 = v58;
    do
    {
      v17 = *((_OWORD *)v14 + 1);
      *v16 = *(_OWORD *)v14;
      v18 = *((_OWORD *)v14 + 2);
      v16[1] = v17;
      v19 = *((_OWORD *)v14 + 3);
      v16[2] = v18;
      v20 = *((_OWORD *)v14 + 4);
      v16[3] = v19;
      v21 = *((_OWORD *)v14 + 5);
      v16[4] = v20;
      v22 = *((_OWORD *)v14 + 6);
      v16[5] = v21;
      v23 = *((_OWORD *)v14 + 7);
      v14 += 16;
      v16[6] = v22;
      v16 += 8;
      *(v16 - 1) = v23;
      --v15;
    }
    while ( v15 );
    v24 = *((_OWORD *)v14 + 1);
    *v16 = *(_OWORD *)v14;
    v16[1] = v24;
    if ( sub_1801693C0(&unk_1823B8E28, 0xFFFFFFFFLL, 128LL) > 0.0 )
    {
      v25 = (float *)sub_1818120A0(&unk_1823B8E28, 0xFFFFFFFFLL);
      if ( !v25 )
        v25 = *(float **)(qword_1823B8E30 + 8);
      if ( v59 != (float)(v59 + *v25) )
      {
        v59 = v59 + *v25;
        sub_1815CF250(v58);
      }
    }
    v26 = *a2;
    v27 = 0;
    v50 = -1073741816;
    v48 = 0;
    v51 = 0LL;
    v28 = *(__int64 (__fastcall **)(__int64 *, const char *, _DWORD *, unsigned int *))(v26 + 8);
    v49 = 0;
    CBufferString::Insert((CBufferString *)&v49, 0, "FirstpersonLegsPrepass", -1, 0);
    v57[0] = 0LL;
    v56 = -1073741696;
    v55 = 0;
    CBufferString::Insert((CBufferString *)&v55, 0, "FirstpersonLegsPrepass", 22, 0);
    CBufferString::ToLowerFast((CBufferString *)&v55, 0);
    v29 = (unsigned __int8 *)&unk_181915088;
    if ( (v56 & 0x40000000) != 0 )
    {
      v30 = (unsigned __int8 *)v57;
    }
    else
    {
      v30 = (unsigned __int8 *)&unk_181915088;
      if ( (v56 & 0x3FFFFFFF) != 0 )
        v30 = (unsigned __int8 *)v57[0];
    }
    v31 = 826366256;
    v32 = 5LL;
    do
    {
      v33 = 1540483477 * *(_DWORD *)v30;
      v30 += 4;
      v31 = (1540483477 * (v33 ^ HIBYTE(v33))) ^ (1540483477 * v31);
      --v32;
    }
    while ( v32 );
    v34 = v31 ^ (v30[1] << 8);
    v35 = (1540483477 * (v34 ^ *v30)) ^ ((1540483477 * (v34 ^ (unsigned int)*v30)) >> 13);
    v36 = (1540483477 * v35) ^ ((1540483477 * v35) >> 15);
    CBufferString::Purge((CBufferString *)&v55, 0);
    v48 = v36;
    v37 = v28(a2, "FirstpersonLegsPass1", v54, &v48);
    CBufferString::Purge((CBufferString *)&v49, 0);
    v38 = a5;
    *(_QWORD *)(v37 + 168) = a5;
    *(_QWORD *)(v37 + 96) = a4;
    LOBYTE(v27) = a4 != -1;
    *(_BYTE *)(v37 + 160) = 1;
    *(_DWORD *)(v37 + 88) = v27;
    (*(void (__fastcall **)(__int64, _BYTE *))(*(_QWORD *)v37 + 32LL))(v37, v58);
    sub_180173830(v37 + 496, 3512098117LL, 1LL);
    *(_DWORD *)(v37 + 80) |= 0x200u;
    HIWORD(v60) = 771;
    *(_QWORD *)(v37 + 72) |= 0x800000C00uLL;
    *(_QWORD *)(v37 + 1152) |= 0x6000000000000uLL;
    LOWORD(v60) = 3;
    WORD2(v60) = 0;
    *(_BYTE *)(v37 + 1736) = 1;
    WORD1(v60) = 23813;
    WORD2(v60) = WORD2(v60) & 0xFE07 | 0x1D0;
    *(_QWORD *)(v37 + 1716) = v60;
    (*(void (__fastcall **)(__int64, const char *))(*(_QWORD *)v37 + 120LL))(v37, "Firstperson Legs");
    v39 = *a2;
    v50 = -1073741816;
    v48 = 0;
    v51 = 0LL;
    v60 = *(__int64 (__fastcall **)(__int64 *, const char *, _DWORD *, unsigned int *))(v39 + 8);
    v49 = 0;
    CBufferString::Insert((CBufferString *)&v49, 0, "CsgoForward", -1, 0);
    v57[0] = 0LL;
    v56 = -1073741696;
    v55 = 0;
    CBufferString::Insert((CBufferString *)&v55, 0, "CsgoForward", 11, 0);
    CBufferString::ToLowerFast((CBufferString *)&v55, 0);
    if ( (v56 & 0x40000000) != 0 )
    {
      v29 = (unsigned __int8 *)v57;
    }
    else if ( (v56 & 0x3FFFFFFF) != 0 )
    {
      v29 = (unsigned __int8 *)v57[0];
    }
    v40 = 826366253;
    v41 = 2LL;
    do
    {
      v42 = 1540483477 * *(_DWORD *)v29;
      v29 += 4;
      v40 = (1540483477 * (v42 ^ HIBYTE(v42))) ^ (1540483477 * v40);
      --v41;
    }
    while ( v41 );
    v43 = (v29[1] << 8) ^ (v29[2] << 16) ^ v40 ^ *v29;
    v44 = (1540483477 * ((1540483477 * v43) ^ ((unsigned int)(1540483477 * v43) >> 13))) ^ ((1540483477
                                                                                           * ((1540483477 * v43) ^ ((unsigned int)(1540483477 * v43) >> 13))) >> 15);
    CBufferString::Purge((CBufferString *)&v55, 0);
    v48 = v44;
    v45 = v60(a2, "FirstpersonLegsPass2", v54, &v48);
    CBufferString::Purge((CBufferString *)&v49, 0);
    *(_QWORD *)(v45 + 168) = v38;
    *(_DWORD *)(v45 + 88) = v27;
    *(_QWORD *)(v45 + 96) = a4;
    *(_BYTE *)(v45 + 160) = 1;
    (*(void (__fastcall **)(__int64, _BYTE *))(*(_QWORD *)v45 + 32LL))(v45, v58);
    sub_180173830(v45 + 496, 3512098117LL, 1LL);
    *(_QWORD *)(v45 + 72) |= 0x10401C00uLL;
    *(_QWORD *)(v45 + 1152) |= 0x6000000000000uLL;
    *(_DWORD *)((char *)&v47 + 2) = 0;
    HIWORD(v47) = 0;
    if ( dword_1822B5E10 > *(_DWORD *)(*((_QWORD *)NtCurrentTeb()->ThreadLocalStoragePointer + (unsigned int)TlsIndex)
                                     + 152LL) )
    {
      sub_18185B1B8(&dword_1822B5E10);
      if ( dword_1822B5E10 == -1 )
      {
        qword_1822B5E08 = 0xFFFF01C01C000303uLL;
        sub_18185B14C(&dword_1822B5E10);
      }
    }
    LOBYTE(v47) = qword_1822B5E08 | 3;
    BYTE1(v47) = 2;
    LODWORD(v60) = 8390657;
    *(_DWORD *)((char *)&v47 + 2) = 8390657;
    WORD2(v60) = 3;
    HIWORD(v47) = 3;
    v46 = (*(__int64 (__fastcall **)(__int64, __int64 *))(*(_QWORD *)qword_18253FAE8 + 248LL))(qword_18253FAE8, &v47);
    *(_DWORD *)(v45 + 1740) = 3;
    *(_QWORD *)(v45 + 1680) = v46;
    (*(void (__fastcall **)(__int64, const char *))(*(_QWORD *)v45 + 120LL))(v45, "Firstperson Legs");
    v60 = (__int64 (__fastcall *)(__int64 *, const char *, _DWORD *, unsigned int *))v37;
    sub_181107EE0(v45 + 1784, &v60);
  }
}
