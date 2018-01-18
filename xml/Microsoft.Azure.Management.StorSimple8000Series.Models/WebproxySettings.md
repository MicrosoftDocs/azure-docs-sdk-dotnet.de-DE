<Type Name="WebproxySettings" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings">
  <TypeSignature Language="C#" Value="public class WebproxySettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebproxySettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings" />
  <TypeSignature Language="VB.NET" Value="Public Class WebproxySettings" />
  <TypeSignature Language="F#" Value="type WebproxySettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7b610-101">Die Webproxyeinstellungen auf dem Gerät.</span><span class="sxs-lookup"><span data-stu-id="7b610-101">The web proxy settings on the device.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebproxySettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7b610-102">Initialisiert eine neue Instanz der WebproxySettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7b610-102">Initializes a new instance of the WebproxySettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebproxySettings (Microsoft.Azure.Management.StorSimple8000Series.Models.AuthenticationType authentication, string username, string connectionUri = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AuthenticationType authentication, string username, string connectionUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings.#ctor(Microsoft.Azure.Management.StorSimple8000Series.Models.AuthenticationType,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (authentication As AuthenticationType, username As String, Optional connectionUri As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings : Microsoft.Azure.Management.StorSimple8000Series.Models.AuthenticationType * string * string -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings (authentication, username, connectionUri)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="authentication" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AuthenticationType" />
        <Parameter Name="username" Type="System.String" />
        <Parameter Name="connectionUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="authentication"><span data-ttu-id="7b610-103">Der Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="7b610-103">The authentication type.</span></span> <span data-ttu-id="7b610-104">Folgende Werte sind möglich: "Ungültig", "None", "Basic", "NTLM"</span><span class="sxs-lookup"><span data-stu-id="7b610-104">Possible values include: 'Invalid', 'None', 'Basic', 'NTLM'</span></span></param>
        <param name="username"><span data-ttu-id="7b610-105">Der Webproxy-Benutzername.</span><span class="sxs-lookup"><span data-stu-id="7b610-105">The webproxy username.</span></span></param>
        <param name="connectionUri"><span data-ttu-id="7b610-106">Der Verbindungs-URI.</span><span class="sxs-lookup"><span data-stu-id="7b610-106">The connection URI.</span></span></param>
        <summary>
            <span data-ttu-id="7b610-107">Initialisiert eine neue Instanz der WebproxySettings-Klasse.</span><span class="sxs-lookup"><span data-stu-id="7b610-107">Initializes a new instance of the WebproxySettings class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Authentication">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AuthenticationType Authentication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.AuthenticationType Authentication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings.Authentication" />
      <MemberSignature Language="VB.NET" Value="Public Property Authentication As AuthenticationType" />
      <MemberSignature Language="F#" Value="member this.Authentication : Microsoft.Azure.Management.StorSimple8000Series.Models.AuthenticationType with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings.Authentication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="authentication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AuthenticationType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b610-108">Ruft ab oder legt den Authentifizierungstyp.</span><span class="sxs-lookup"><span data-stu-id="7b610-108">Gets or sets the authentication type.</span></span> <span data-ttu-id="7b610-109">Folgende Werte sind möglich: "Ungültig", "None", "Basic", "NTLM"</span><span class="sxs-lookup"><span data-stu-id="7b610-109">Possible values include: 'Invalid', 'None', 'Basic', 'NTLM'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionUri">
      <MemberSignature Language="C#" Value="public string ConnectionUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings.ConnectionUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionUri As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionUri : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings.ConnectionUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b610-110">Ruft ab oder legt den Verbindungs-URI.</span><span class="sxs-lookup"><span data-stu-id="7b610-110">Gets or sets the connection URI.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Username">
      <MemberSignature Language="C#" Value="public string Username { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Username" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings.Username" />
      <MemberSignature Language="VB.NET" Value="Public Property Username As String" />
      <MemberSignature Language="F#" Value="member this.Username : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings.Username" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="username")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7b610-111">Ruft ab, oder legt ihn fest Webproxy-Benutzername.</span><span class="sxs-lookup"><span data-stu-id="7b610-111">Gets or sets the webproxy username.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.WebproxySettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="webproxySettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="7b610-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="7b610-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7b610-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="7b610-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>