<Type Name="ProviderCredentials" FullName="Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials">
  <TypeSignature Language="C#" Value="public abstract class ProviderCredentials" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ProviderCredentials extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ProviderCredentials" />
  <TypeSignature Language="F#" Value="type ProviderCredentials = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="64d52-101">Die Basisklasse für alle Anbieter bestimmte Anmeldeinformationen.</span><span class="sxs-lookup"><span data-stu-id="64d52-101">Base class for all provider specific credentials.</span></span> <span data-ttu-id="64d52-102">Anbieter-spezifischen Unterklassen enthalten fügen eigene spezifische Informationen hinzu, z. B. Zugriff auf Token, token geheime Schlüssel usw.</span><span class="sxs-lookup"><span data-stu-id="64d52-102">Provider specific subclasses include add their own specific information, for example access tokens, token secrets, etc.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ProviderCredentials (string providerName);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(string providerName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (providerName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials : string -&gt; Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials" Usage="new Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials providerName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="providerName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="providerName"><span data-ttu-id="64d52-103">Der Name des Anbieters.</span><span class="sxs-lookup"><span data-stu-id="64d52-103">The name of the provider.</span></span></param>
        <summary>
            <span data-ttu-id="64d52-104">Initialisiert eine neue Instanz mit dem Namen des Anbieters, die dieser Instanz zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="64d52-104">Initializes a new instance with the name of the provider associated with this instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public string Provider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials.Provider" />
      <MemberSignature Language="VB.NET" Value="Public Property Provider As String" />
      <MemberSignature Language="F#" Value="member this.Provider : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials.Provider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64d52-105">Ruft ab oder legt den Namen des Anbieters ein, die für diese Anmeldeinformationen sind.</span><span class="sxs-lookup"><span data-stu-id="64d52-105">Gets or sets the name of the provider these credentials are for.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserClaims">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;System.Security.Claims.Claim&gt; UserClaims { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IEnumerable`1&lt;class System.Security.Claims.Claim&gt; UserClaims" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials.UserClaims" />
      <MemberSignature Language="VB.NET" Value="Public Property UserClaims As IEnumerable(Of Claim)" />
      <MemberSignature Language="F#" Value="member this.UserClaims : seq&lt;System.Security.Claims.Claim&gt; with get, set" Usage="Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials.UserClaims" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(NullValueHandling=Newtonsoft.Json.NullValueHandling.Ignore)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;System.Security.Claims.Claim&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64d52-106">Ruft ab oder legt die Auflistung der zusätzliche Ansprüche, die dieser Instanz zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="64d52-106">Gets or sets the collection of additional claims associated with this instance.</span></span> <span data-ttu-id="64d52-107">Kann null oder leer sein.</span><span class="sxs-lookup"><span data-stu-id="64d52-107">May be null or empty.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserId">
      <MemberSignature Language="C#" Value="public string UserId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UserId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials.UserId" />
      <MemberSignature Language="VB.NET" Value="Public Property UserId As String" />
      <MemberSignature Language="F#" Value="member this.UserId : string with get, set" Usage="Microsoft.Azure.Mobile.Server.Authentication.ProviderCredentials.UserId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.Authentication</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonIgnore</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="64d52-108">Ruft ab oder legt die Anbieter-Id für den Benutzer fest.</span><span class="sxs-lookup"><span data-stu-id="64d52-108">Gets or sets the provider id for the user.</span></span> <span data-ttu-id="64d52-109">Der Wert kann erstellt werden, und mithilfe der bereitgestellten Methoden analysiert <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler" />.</span><span class="sxs-lookup"><span data-stu-id="64d52-109">The value can be created and parsed using the methods provided by <see cref="T:Microsoft.Azure.Mobile.Server.Authentication.IAppServiceTokenHandler" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>