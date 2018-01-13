<Type Name="IMobileAppSettingsProvider" FullName="Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider">
  <TypeSignature Language="C#" Value="public interface IMobileAppSettingsProvider" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileAppSettingsProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileAppSettingsProvider" />
  <TypeSignature Language="F#" Value="type IMobileAppSettingsProvider = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Stellt eine Abstraktion zum Abrufen der <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" /> für einen Dienst. Die <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" /> enthält Einstellungen wie den Namen und andere Parameter für den Dienst.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetMobileAppSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary GetMobileAppSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary GetMobileAppSettings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider.GetMobileAppSettings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMobileAppSettings () As MobileAppSettingsDictionary" />
      <MemberSignature Language="F#" Value="abstract member GetMobileAppSettings : unit -&gt; Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" Usage="iMobileAppSettingsProvider.GetMobileAppSettings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" /> für diesen Dienst ab.
            </summary>
        <returns>Eine initialisierte <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" /> Instanz.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>