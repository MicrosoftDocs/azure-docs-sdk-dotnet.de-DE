<Type Name="ValidateCustomDomainInput" FullName="Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainInput">
  <TypeSignature Language="C#" Value="public class ValidateCustomDomainInput" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ValidateCustomDomainInput extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainInput" />
  <TypeSignature Language="VB.NET" Value="Public Class ValidateCustomDomainInput" />
  <TypeSignature Language="F#" Value="type ValidateCustomDomainInput = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6d113-101">Die Eingabe der benutzerdefinierten Domäne für die DNS-Zuordnung überprüft werden.</span><span class="sxs-lookup"><span data-stu-id="6d113-101">Input of the custom domain to be validated for DNS mapping.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateCustomDomainInput ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainInput.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6d113-102">Initialisiert eine neue Instanz der ValidateCustomDomainInput-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6d113-102">Initializes a new instance of the ValidateCustomDomainInput class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ValidateCustomDomainInput (string hostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string hostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainInput.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (hostName As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainInput : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainInput" Usage="new Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainInput hostName" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName"><span data-ttu-id="6d113-103">Der Hostname der benutzerdefinierten Domäne.</span><span class="sxs-lookup"><span data-stu-id="6d113-103">The host name of the custom domain.</span></span> <span data-ttu-id="6d113-104">Ein Domänenname muss sein.</span><span class="sxs-lookup"><span data-stu-id="6d113-104">Must be a domain name.</span></span></param>
        <summary>
            <span data-ttu-id="6d113-105">Initialisiert eine neue Instanz der ValidateCustomDomainInput-Klasse.</span><span class="sxs-lookup"><span data-stu-id="6d113-105">Initializes a new instance of the ValidateCustomDomainInput class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainInput.HostName" />
      <MemberSignature Language="VB.NET" Value="Public Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string with get, set" Usage="Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainInput.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="hostName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="6d113-106">Ruft ab oder legt den Hostnamen der benutzerdefinierten Domäne fest.</span><span class="sxs-lookup"><span data-stu-id="6d113-106">Gets or sets the host name of the custom domain.</span></span> <span data-ttu-id="6d113-107">Ein Domänenname muss sein.</span><span class="sxs-lookup"><span data-stu-id="6d113-107">Must be a domain name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.Models.ValidateCustomDomainInput.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="validateCustomDomainInput.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="6d113-108">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="6d113-108">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="6d113-109">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="6d113-109">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>