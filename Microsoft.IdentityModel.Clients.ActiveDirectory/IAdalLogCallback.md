<Type Name="IAdalLogCallback" FullName="Microsoft.IdentityModel.Clients.ActiveDirectory.IAdalLogCallback">
  <TypeSignature Language="C#" Value="public interface IAdalLogCallback" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAdalLogCallback" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Clients.ActiveDirectory.IAdalLogCallback" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAdalLogCallback" />
  <TypeSignature Language="F#" Value="type IAdalLogCallback = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
    <AssemblyVersion>3.16.0.14</AssemblyVersion>
    <AssemblyVersion>3.17.3.35304</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c6d26-101">Rückruf für das Erfassen von ADAL meldet benutzerdefinierte Protokollierung Schemas.</span><span class="sxs-lookup"><span data-stu-id="c6d26-101">Callback for capturing ADAL logs to custom logging schemes.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Log">
      <MemberSignature Language="C#" Value="public void Log (Microsoft.IdentityModel.Clients.ActiveDirectory.LogLevel level, string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Log(valuetype Microsoft.IdentityModel.Clients.ActiveDirectory.LogLevel level, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Clients.ActiveDirectory.IAdalLogCallback.Log(Microsoft.IdentityModel.Clients.ActiveDirectory.LogLevel,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Log (level As LogLevel, message As String)" />
      <MemberSignature Language="F#" Value="abstract member Log : Microsoft.IdentityModel.Clients.ActiveDirectory.LogLevel * string -&gt; unit" Usage="iAdalLogCallback.Log (level, message)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Clients.ActiveDirectory</AssemblyName>
        <AssemblyVersion>3.16.0.14</AssemblyVersion>
        <AssemblyVersion>3.17.3.35304</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="level" Type="Microsoft.IdentityModel.Clients.ActiveDirectory.LogLevel" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="level"><span data-ttu-id="c6d26-102">Protokolliergrad</span><span class="sxs-lookup"><span data-stu-id="c6d26-102">Log level</span></span></param>
        <param name="message"><span data-ttu-id="c6d26-103">die zu protokollierende Meldung</span><span class="sxs-lookup"><span data-stu-id="c6d26-103">message to be logged</span></span></param>
        <summary>
            <span data-ttu-id="c6d26-104">Rückrufmethode, die für die benutzerdefinierte Protokollierung zu implementieren.</span><span class="sxs-lookup"><span data-stu-id="c6d26-104">Callback method to implement for custom logging</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>