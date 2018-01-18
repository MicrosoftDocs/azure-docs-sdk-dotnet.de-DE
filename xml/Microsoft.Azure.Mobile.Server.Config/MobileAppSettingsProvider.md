<Type Name="MobileAppSettingsProvider" FullName="Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider">
  <TypeSignature Language="C#" Value="public class MobileAppSettingsProvider : Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileAppSettingsProvider extends System.Object implements class Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileAppSettingsProvider&#xA;Implements IMobileAppSettingsProvider" />
  <TypeSignature Language="F#" Value="type MobileAppSettingsProvider = class&#xA;    interface IMobileAppSettingsProvider" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="89c1a-101">Stellt eine Standardimplementierung von <see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider" /> die Ruft die Einstellungen für den Dienst ab, aus der globalen <see cref="T:System.Configuration.ConfigurationManager" />.</span><span class="sxs-lookup"><span data-stu-id="89c1a-101">Provides a default implementation of <see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider" /> which gets the settings for the service from the global <see cref="T:System.Configuration.ConfigurationManager" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileAppSettingsProvider ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="89c1a-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="89c1a-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppSettings">
      <MemberSignature Language="C#" Value="protected virtual System.Collections.Specialized.NameValueCollection GetAppSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Collections.Specialized.NameValueCollection GetAppSettings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider.GetAppSettings" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function GetAppSettings () As NameValueCollection" />
      <MemberSignature Language="F#" Value="abstract member GetAppSettings : unit -&gt; System.Collections.Specialized.NameValueCollection&#xA;override this.GetAppSettings : unit -&gt; System.Collections.Specialized.NameValueCollection" Usage="mobileAppSettingsProvider.GetAppSettings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Specialized.NameValueCollection</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="89c1a-103">Ruft die aktuellen Anwendungseinstellungen auf mockable Weise.</span><span class="sxs-lookup"><span data-stu-id="89c1a-103">Gets the current application settings in a mockable manner.</span></span>
            </summary>
        <returns><span data-ttu-id="89c1a-104">Ein <see cref="T:System.Collections.Specialized.NameValueCollection" /> mit den Anwendungseinstellungen.</span><span class="sxs-lookup"><span data-stu-id="89c1a-104">A <see cref="T:System.Collections.Specialized.NameValueCollection" /> containing the application settings.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMobileAppSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary GetMobileAppSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary GetMobileAppSettings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider.GetMobileAppSettings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetMobileAppSettings () As MobileAppSettingsDictionary" />
      <MemberSignature Language="F#" Value="abstract member GetMobileAppSettings : unit -&gt; Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary&#xA;override this.GetMobileAppSettings : unit -&gt; Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" Usage="mobileAppSettingsProvider.GetMobileAppSettings " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Mobile.Server.Config.IMobileAppSettingsProvider.GetMobileAppSettings</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="InitializeSettings">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary InitializeSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary InitializeSettings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppSettingsProvider.InitializeSettings" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function InitializeSettings () As MobileAppSettingsDictionary" />
      <MemberSignature Language="F#" Value="abstract member InitializeSettings : unit -&gt; Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary&#xA;override this.InitializeSettings : unit -&gt; Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" Usage="mobileAppSettingsProvider.InitializeSettings " />
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
            <span data-ttu-id="89c1a-105">Initialisiert die <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" /> bereitgestellt, die als Antwort auf <see cref="M:GetMobileAppSettings" />.</span><span class="sxs-lookup"><span data-stu-id="89c1a-105">Initializes the <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" /> provided in response to <see cref="M:GetMobileAppSettings" />.</span></span>
            </summary>
        <returns><span data-ttu-id="89c1a-106">Einen vollständig initialisierten <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" />.</span><span class="sxs-lookup"><span data-stu-id="89c1a-106">A fully initialized <see cref="T:Microsoft.Azure.Mobile.Server.MobileAppSettingsDictionary" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>