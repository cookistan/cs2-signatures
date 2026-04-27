
flashbang overlay strings - client.dll

FlashbangOverlay
cs_flash_frame_render_target_split_%d

void __fastcall flashOverlay(__int64 a1, int a2, __int64 *a3, __int64 a4, __m128 *a5)
{
  __int64 v6; // r15
  __int64 v9; // rax
  __int64 v10; // rdi
  __m128 v11; // xmm6
  __int64 v12; // rbx
  __int64 v13; // rax
  __int64 v14; // rcx
  unsigned int v15; // r12d
  __m128 v16; // xmm0
  unsigned __int64 v17; // xmm1_8
  __int64 v18; // rax
  __int64 (__fastcall *v19)(__int64 *, const char *, __m128 *, __int64, _QWORD *, _BYTE); // r10
  __int64 v20; // r9
  __int64 v21; // rax
  int v22; // r8d
  __int64 v23; // r13
  CBufferString *v24; // rcx
  _QWORD *v25; // rdx
  void *v26; // rsi
  unsigned __int8 *v27; // rdx
  int v28; // r8d
  __int64 v29; // r9
  unsigned int v30; // eax
  int v31; // eax
  unsigned int v32; // ebx
  __m128 v33; // xmm0
  __int64 (__fastcall *v34)(__int64 *, void *, __int64, _QWORD); // rbx
  __int64 v35; // rdi
  __int64 v36; // rax
  int v37; // ecx
  __int64 v38; // rbx
  __m128 v39; // [rsp+30h] [rbp-D0h] BYREF
  unsigned __int64 v40; // [rsp+40h] [rbp-C0h]
  __int32 v41; // [rsp+48h] [rbp-B8h]
  _QWORD v42[2]; // [rsp+50h] [rbp-B0h] BYREF
  __int128 v43; // [rsp+60h] [rbp-A0h]
  __int128 v44; // [rsp+70h] [rbp-90h]
  __int128 v45; // [rsp+80h] [rbp-80h]
  __int128 v46; // [rsp+90h] [rbp-70h]
  __int128 v47; // [rsp+A0h] [rbp-60h]
  __int128 v48; // [rsp+B0h] [rbp-50h]
  __int128 v49; // [rsp+C0h] [rbp-40h]
  int v50; // [rsp+D0h] [rbp-30h] BYREF
  int v51; // [rsp+D4h] [rbp-2Ch]
  unsigned __int8 *v52; // [rsp+D8h] [rbp-28h] BYREF

  if ( a2 >= 0 )
  {
    v6 = a2;
    v9 = sub_180BD65B0();
    v10 = v9;
    if ( v9 )
    {
      v11 = (__m128)0x3F800000u;
      if ( (*(unsigned __int8 (__fastcall **)(__int64))(*(_QWORD *)v9 + 2736LL))(v9) )
      {
        v12 = v10;
        v13 = sub_1807D8790(v10);
        v14 = v10;
        if ( v13 )
          v10 = v13;
        if ( (unsigned int)sub_1807D86F0(v14) == 2 && (unsigned __int8)sub_180C3B3D0() )
        {
          v11 = (__m128)0x3F19999Au;
        }
        else if ( (unsigned int)sub_1807D86F0(v12) == 1 || (unsigned int)sub_1807D86F0(v12) == 4 )
        {
          v11 = (__m128)0x3E4CCCCDu;
        }
        else if ( (unsigned int)sub_1807D86F0(v12) != 2 )
        {
          v11 = (__m128)0x3F19999Au;
        }
      }
      if ( *(float *)(v10 + 5120) > 0.0
        && *(float *)(v10 + 5100) > *((float *)off_1820496A0 + 12)
        && !(unsigned __int8)sub_180701100(qword_182328F38)
        && !(unsigned __int8)sub_180701A70(qword_182328F38) )
      {
        v15 = 1;
        if ( !*(_BYTE *)(v10 + 5114) )
        {
          v16 = *a5;
          v41 = a5[1].m128_i32[2];
          v17 = a5[1].m128_u64[0];
          v39 = v16;
          v40 = v17;
          sub_181137790(a1, (unsigned int)v6, a3, a4, &v39);
          *(_BYTE *)(v10 + 5114) = 1;
          v15 = 0;
        }
        v42[1] = a4;
        v42[0] = a4 != -1;
        v18 = *a3;
        v46 = 0LL;
        BYTE8(v46) = 1;
        v47 = 0LL;
        v19 = *(__int64 (__fastcall **)(__int64 *, const char *, __m128 *, __int64, _QWORD *, _BYTE))(v18 + 80);
        *(_QWORD *)&v47 = -1LL;
        v43 = 0LL;
        v44 = 0LL;
        v45 = 0LL;
        v48 = 0LL;
        v49 = 0LL;
        if ( qword_1823B8930 )
          v20 = *(_QWORD *)qword_1823B8930;
        else
          v20 = 0LL;
        v21 = v19(a3, "FlashbangOverlay", a5, v20, v42, 0);
        v22 = *(_DWORD *)(v21 + 60);
        v23 = v21;
        v24 = (CBufferString *)(v21 + 56);
        if ( (v22 & 0x3FFFFFFF) != 0 )
        {
          v25 = (_QWORD *)(v21 + 64);
          if ( (v22 & 0x40000000) == 0 )
            v25 = (_QWORD *)*v25;
          *(_BYTE *)v25 = 0;
        }
        *(_DWORD *)v24 &= 0xC0000000;
        CBufferString::Insert(v24, 0, "CsgoForward", -1, 0);
        v51 = -1073741696;
        v52 = 0LL;
        v50 = 0;
        CBufferString::Insert((CBufferString *)&v50, 0, "CsgoForward", 11, 0);
        CBufferString::ToLowerFast((CBufferString *)&v50, 0);
        v26 = &unk_181915088;
        if ( (v51 & 0x40000000) != 0 )
        {
          v27 = (unsigned __int8 *)&v52;
        }
        else
        {
          v27 = (unsigned __int8 *)&unk_181915088;
          if ( (v51 & 0x3FFFFFFF) != 0 )
            v27 = v52;
        }
        v28 = 826366253;
        v29 = 2LL;
        do
        {
          v30 = 1540483477 * *(_DWORD *)v27;
          v27 += 4;
          v28 = (1540483477 * (v30 ^ HIBYTE(v30))) ^ (1540483477 * v28);
          --v29;
        }
        while ( v29 );
        v31 = (v27[1] << 8) ^ (v27[2] << 16) ^ v28 ^ *v27;
        v32 = 1540483477 * ((1540483477 * v31) ^ ((unsigned int)(1540483477 * v31) >> 13));
        CBufferString::Purge((CBufferString *)&v50, 0);
        v33 = v11;
        *(_DWORD *)(v23 + 48) = v32 ^ (v32 >> 15);
        v33.m128_f32[0] = v11.m128_f32[0] * *(float *)(v10 + 5108);
        v39 = _mm_shuffle_ps(v33, v33, 0);
        sub_180173C60(v23 + 224, 1205610556LL, &v39);
        v11.m128_f32[0] = v11.m128_f32[0] * *(float *)(v10 + 5104);
        v39 = _mm_shuffle_ps(v11, v11, 0);
        sub_180173C60(v23 + 224, 4030147780LL, &v39);
        sub_180173830(v23 + 496, 3890655238LL, v15);
        v34 = *(__int64 (__fastcall **)(__int64 *, void *, __int64, _QWORD))(*a3 + 712);
        v35 = *(_QWORD *)(a1 + 16 * v6);
        v36 = sub_18014EA80(&v50, "cs_flash_frame_render_target_split_%d", v6);
        v37 = *(_DWORD *)(v36 + 4);
        if ( (v37 & 0x40000000) != 0 )
        {
          v26 = (void *)(v36 + 8);
        }
        else if ( (v37 & 0x3FFFFFFF) != 0 )
        {
          v26 = *(void **)(v36 + 8);
        }
        v38 = v34(a3, v26, v35, 0LL);
        CBufferString::Purge((CBufferString *)&v50, 0);
        sub_181132730(v23, 3512961306LL, v38, 0LL, 1, 0);
      }
    }
  }
}
