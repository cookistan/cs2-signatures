draw team intro strings - client.dll

team_intro_start
team_intro_end

void __fastcall drawTeamIntro(__int64 a1, __int64 a2, char *a3)
{
  char v3; // r9
  const char *v4; // rdx
  __int64 v5; // rax

  v3 = *a3;
  if ( *(_BYTE *)(a1 + 3844) != *a3 )
  {
    *(_BYTE *)(a1 + 3844) = v3;
    v4 = "team_intro_end";
    if ( v3 )
      v4 = "team_intro_start";
    v5 = (*(__int64 (__fastcall **)(__int64, const char *, _QWORD, _QWORD))(*(_QWORD *)qword_182311338 + 48LL))(
           qword_182311338,
           v4,
           0LL,
           0LL);
    if ( v5 )
      (*(void (__fastcall **)(__int64, __int64))(*(_QWORD *)qword_182311338 + 64LL))(qword_182311338, v5);
  }
}
