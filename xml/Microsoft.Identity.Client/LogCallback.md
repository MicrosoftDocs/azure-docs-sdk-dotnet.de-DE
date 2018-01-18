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
    <param name="level"><span data-ttu-id="115a4-101">Protokollebene der Meldung</span><span class="sxs-lookup"><span data-stu-id="115a4-101">Log level of the message</span></span></param>
    <param name="message"><span data-ttu-id="115a4-102">Vorformatierte protokollmeldung</span><span class="sxs-lookup"><span data-stu-id="115a4-102">Pre-formatted log message</span></span></param>
    <param name="containsPii"><span data-ttu-id="115a4-103">Gibt an, ob die protokollmeldung personenbezogene Daten enthält.</span><span class="sxs-lookup"><span data-stu-id="115a4-103">Indicates if the log message contains PII.</span></span> <span data-ttu-id="115a4-104">Wenn Logger.PiiLoggingEnabled auf "false" festgelegt ist, ist dieser Wert immer "false".</span><span class="sxs-lookup"><span data-stu-id="115a4-104">If Logger.PiiLoggingEnabled is set to false then this value is always false.</span></span></param>
    <summary>
            <span data-ttu-id="115a4-105">Rückrufdelegat, der den Entwickler, die Protokolle nutzen kann, die sie auf benutzerdefinierte Weise behandeln.</span><span class="sxs-lookup"><span data-stu-id="115a4-105">Callback delegate that allows the developer to consume logs handle them in a custom manner.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
</Type>