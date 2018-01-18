<Type Name="IssuerCredentials" FullName="Microsoft.Azure.KeyVault.Models.IssuerCredentials">
  <TypeSignature Language="C#" Value="public class IssuerCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IssuerCredentials extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.IssuerCredentials" />
  <TypeSignature Language="VB.NET" Value="Public Class IssuerCredentials" />
  <TypeSignature Language="F#" Value="type IssuerCredentials = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="87ad3-101">Die Anmeldeinformationen für den Aussteller des Zertifikats verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="87ad3-101">The credentials to be used for the certificate issuer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IssuerCredentials ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.IssuerCredentials.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="87ad3-102">Initialisiert eine neue Instanz der IssuerCredentials-Klasse.</span><span class="sxs-lookup"><span data-stu-id="87ad3-102">Initializes a new instance of the IssuerCredentials class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IssuerCredentials (string accountId = null, string password = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string accountId, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.IssuerCredentials.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional accountId As String = null, Optional password As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.IssuerCredentials : string * string -&gt; Microsoft.Azure.KeyVault.Models.IssuerCredentials" Usage="new Microsoft.Azure.KeyVault.Models.IssuerCredentials (accountId, password)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="accountId" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="accountId"><span data-ttu-id="87ad3-103">Die Name-Konto-Id Benutzer oder der Name des Kontos.</span><span class="sxs-lookup"><span data-stu-id="87ad3-103">The user name/account name/account id.</span></span></param>
        <param name="password"><span data-ttu-id="87ad3-104">Der Konto/Kennwort/Secret-Schlüssel.</span><span class="sxs-lookup"><span data-stu-id="87ad3-104">The password/secret/account key.</span></span></param>
        <summary>
            <span data-ttu-id="87ad3-105">Initialisiert eine neue Instanz der IssuerCredentials-Klasse.</span><span class="sxs-lookup"><span data-stu-id="87ad3-105">Initializes a new instance of the IssuerCredentials class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccountId">
      <MemberSignature Language="C#" Value="public string AccountId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AccountId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerCredentials.AccountId" />
      <MemberSignature Language="VB.NET" Value="Public Property AccountId As String" />
      <MemberSignature Language="F#" Value="member this.AccountId : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.IssuerCredentials.AccountId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="account_id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87ad3-106">Ruft ab, oder legt Sie die Benutzer oder der Name des Kontos Name-Konto-Id fest.</span><span class="sxs-lookup"><span data-stu-id="87ad3-106">Gets or sets the user name/account name/account id.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.IssuerCredentials.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.KeyVault.Models.IssuerCredentials.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pwd")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="87ad3-107">Ruft ab oder legt das Kennwort, geheime Schlüssel/kontoschlüssel.</span><span class="sxs-lookup"><span data-stu-id="87ad3-107">Gets or sets the password/secret/account key.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>