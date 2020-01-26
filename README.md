# MP3Player
 Basic C# Web Forms MP3 Player

using System.Runtime.InteropServices;

[DllImport("winmm.dll")]
        private static extern long mciSendString(string strCommand, StringBuilder strReturn, int iReturnLength, IntPtr hwndCallback);
