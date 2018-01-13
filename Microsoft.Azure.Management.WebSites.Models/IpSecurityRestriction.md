<Type Name="IpSecurityRestriction" FullName="Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction">
  <TypeSignature Language="C#" Value="public class IpSecurityRestriction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IpSecurityRestriction extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction" />
  <TypeSignature Language="VB.NET" Value="Public Class IpSecurityRestriction" />
  <TypeSignature Language="F#" Value="type IpSecurityRestriction = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1e3e0-101">Einschränkung für die IP-Sicherheit für eine app.</span><span class="sxs-lookup"><span data-stu-id="1e3e0-101">IP security restriction on an app.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IpSecurityRestriction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e3e0-102">Initialisiert eine neue Instanz der IpSecurityRestriction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1e3e0-102">Initializes a new instance of the IpSecurityRestriction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IpSecurityRestriction (string ipAddress, string subnetMask = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string ipAddress, string subnetMask) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (ipAddress As String, Optional subnetMask As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction : string * string -&gt; Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction" Usage="new Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction (ipAddress, subnetMask)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
        <Parameter Name="subnetMask" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress"><span data-ttu-id="1e3e0-103">IP-Adresse die sicherheitsbeschränkung ist gültig.</span><span class="sxs-lookup"><span data-stu-id="1e3e0-103">IP address the security restriction is valid for.</span></span></param>
        <param name="subnetMask"><span data-ttu-id="1e3e0-104">Subnetzmaske ist für die IP-Einschränkung Adressen für gültig.</span><span class="sxs-lookup"><span data-stu-id="1e3e0-104">Subnet mask for the range of IP addresses the restriction is valid for.</span></span></param>
        <summary>
            <span data-ttu-id="1e3e0-105">Initialisiert eine neue Instanz der IpSecurityRestriction-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1e3e0-105">Initializes a new instance of the IpSecurityRestriction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IpAddress">
      <MemberSignature Language="C#" Value="public string IpAddress { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string IpAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction.IpAddress" />
      <MemberSignature Language="VB.NET" Value="Public Property IpAddress As String" />
      <MemberSignature Language="F#" Value="member this.IpAddress : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction.IpAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ipAddress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e3e0-106">Ruft ab oder legt die IP-Adresse, die die sicherheitsbeschränkung für gültig ist.</span><span class="sxs-lookup"><span data-stu-id="1e3e0-106">Gets or sets IP address the security restriction is valid for.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubnetMask">
      <MemberSignature Language="C#" Value="public string SubnetMask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubnetMask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction.SubnetMask" />
      <MemberSignature Language="VB.NET" Value="Public Property SubnetMask As String" />
      <MemberSignature Language="F#" Value="member this.SubnetMask : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction.SubnetMask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subnetMask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e3e0-107">Ruft ab, oder legt ihn fest Subnetzmaske im Bereich von IP-Adressen, die die Einschränkung für gültig ist.</span><span class="sxs-lookup"><span data-stu-id="1e3e0-107">Gets or sets subnet mask for the range of IP addresses the restriction is valid for.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.IpSecurityRestriction.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="ipSecurityRestriction.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e3e0-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="1e3e0-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="1e3e0-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="1e3e0-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>