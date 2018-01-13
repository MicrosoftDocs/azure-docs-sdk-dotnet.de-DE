<Type Name="LogCallback" FullName="Microsoft.Identity.Client.LogCallback">
  <TypeSignature Language="C#" Value="public delegate void LogCallback(Logger.LogLevel level, string message, bool containsPii);" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed LogCallback extends System.MulticastDelegate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Identity.Client.LogCallback" />
  <TypeSignature Language="VB.NET" Value="Public Delegate Sub LogCallback(level As Logger.LogLevel, message As String, containsPii As Boolean)" />
  <TypeSignature Language="F#" Value="type LogCallback = delegate of Logger.LogLevel * string * bool -&gt; unit" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Identity.Client</AssemblyName>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Delegate</BaseTypeName>
  </Base>
  <Parameters>
    <Parameter Name="level" Type="Microsoft.Identity.Client.Logger+LogLevel" />
    <Parameter Name="message" Type="System.String" />
    <Parameter Name="containsPii" Type="System.Boolean" />
  </Parameters>
  <ReturnValue>
    <ReturnType>System.Void</ReturnType>
  </ReturnValue>
  <Docs>
    <param name="level">Protokollebene der Meldung</param>
    <param name="message">Vorformatierte protokollmeldung</param>
    <param name="containsPii">Gibt an, ob die protokollmeldung personenbezogene Daten enthält. Wenn Logger.PiiLoggingEnabled auf "false" festgelegt ist, ist dieser Wert immer "false".</param>
    <summary>
            Rückrufdelegat, der den Entwickler, die Protokolle nutzen kann, die sie auf benutzerdefinierte Weise behandeln.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>