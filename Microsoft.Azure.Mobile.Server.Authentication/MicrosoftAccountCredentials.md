<Type Name="MicrosoftAccountCredentials" FullName="Microsoft.Azure.Mobile.Server.Authentication.MicrosoftAccountCredentials">
  <TypeSignature Language="C#" Value="public class MicrosoftAccountCredentials : Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MicrosoftAccountCredentials extends Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Authentication.MicrosoftAccountCredentials" />
  <TypeSignature Language="VB.NET" Value="Public Class MicrosoftAccountCredentials&#xA;Inherits ProviderCredentials" />
  <TypeSignature Language="F#" Value="type MicrosoftAccountCredentials = class&#xA;    inherit ProviderCredentials" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="8ce80-101">Ein <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials" /> Implementierung, die Anbieter-spezifischen Anmeldeinformationen für die Microsoft-Account-Authentifizierung.</span><span class="sxs-lookup"><span data-stu-id="8ce80-101">A <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials" /> implementation containing provider specific credentials for Microsoft Account authentication.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MicrosoftAccountCredentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.MicrosoftAccountCredentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="8ce80-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.MicrosoftAccountCredentials" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8ce80-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.MicrosoftAccountCredentials" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessToken">
      <MemberSignature Language="C#" Value="public string AccessToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccessToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Authentication.MicrosoftAccountCredentials.AccessToken" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessToken As String" />
      <MemberSignature Language="F#" Value="member this.AccessToken : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Authentication.MicrosoftAccountCredentials.AccessToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ce80-103">Ruft ab oder legt das Zugriffstoken für den aktuellen Benutzer.</span><span class="sxs-lookup"><span data-stu-id="8ce80-103">Gets or sets the access token for the current user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessTokenExpiration">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTimeOffset&gt; AccessTokenExpiration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; AccessTokenExpiration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Authentication.MicrosoftAccountCredentials.AccessTokenExpiration" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessTokenExpiration As Nullable(Of DateTimeOffset)" />
      <MemberSignature Language="F#" Value="member this.AccessTokenExpiration : Nullable&lt;DateTimeOffset&gt; with get, set" Usage="Microsoft.Azure.Mobile.Server.Authentication.MicrosoftAccountCredentials.AccessTokenExpiration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTimeOffset&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ce80-104">Ruft ab oder legt die Ablaufzeit für das Zugriffstoken.</span><span class="sxs-lookup"><span data-stu-id="8ce80-104">Gets or sets the expiration time for the access token.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshToken">
      <MemberSignature Language="C#" Value="public string RefreshToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RefreshToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Authentication.MicrosoftAccountCredentials.RefreshToken" />
      <MemberSignature Language="VB.NET" Value="Public Property RefreshToken As String" />
      <MemberSignature Language="F#" Value="member this.RefreshToken : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Authentication.MicrosoftAccountCredentials.RefreshToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8ce80-105">Ruft ab oder legt das Aktualisierungstoken, das für den aktuellen Benutzer.</span><span class="sxs-lookup"><span data-stu-id="8ce80-105">Gets or sets the refresh token for the current user.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>