<Type Name="NetworkInterfaceAssociation" FullName="Microsoft.Azure.Management.Network.Models.NetworkInterfaceAssociation">
  <TypeSignature Language="C#" Value="public class NetworkInterfaceAssociation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NetworkInterfaceAssociation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.NetworkInterfaceAssociation" />
  <TypeSignature Language="VB.NET" Value="Public Class NetworkInterfaceAssociation" />
  <TypeSignature Language="F#" Value="type NetworkInterfaceAssociation = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
    <AssemblyVersion>14.0.0.0</AssemblyVersion>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e11f4-101">Die Netzwerkschnittstelle und ihren benutzerdefinierten Regeln.</span><span class="sxs-lookup"><span data-stu-id="e11f4-101">Network interface and its custom security rules.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceAssociation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkInterfaceAssociation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="e11f4-102">Initialisiert eine neue Instanz der NetworkInterfaceAssociation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e11f4-102">Initializes a new instance of the NetworkInterfaceAssociation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NetworkInterfaceAssociation (string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; securityRules = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityRule&gt; securityRules) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.NetworkInterfaceAssociation.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SecurityRule})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional securityRules As IList(Of SecurityRule) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.NetworkInterfaceAssociation : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; -&gt; Microsoft.Azure.Management.Network.Models.NetworkInterfaceAssociation" Usage="new Microsoft.Azure.Management.Network.Models.NetworkInterfaceAssociation (id, securityRules)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="securityRules" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="e11f4-103">Netzwerk-Schnittstellen-ID.</span><span class="sxs-lookup"><span data-stu-id="e11f4-103">Network interface ID.</span></span></param>
        <param name="securityRules"><span data-ttu-id="e11f4-104">Die Auflistung von benutzerdefinierten Sicherheitsregeln.</span><span class="sxs-lookup"><span data-stu-id="e11f4-104">Collection of custom security rules.</span></span></param>
        <summary>
            <span data-ttu-id="e11f4-105">Initialisiert eine neue Instanz der NetworkInterfaceAssociation-Klasse.</span><span class="sxs-lookup"><span data-stu-id="e11f4-105">Initializes a new instance of the NetworkInterfaceAssociation class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceAssociation.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceAssociation.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e11f4-106">Ruft Netzwerk-Schnittstellen-ID.</span><span class="sxs-lookup"><span data-stu-id="e11f4-106">Gets network interface ID.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityRules">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; SecurityRules { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityRule&gt; SecurityRules" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.NetworkInterfaceAssociation.SecurityRules" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityRules As IList(Of SecurityRule)" />
      <MemberSignature Language="F#" Value="member this.SecurityRules : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.NetworkInterfaceAssociation.SecurityRules" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="securityRules")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityRule&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e11f4-107">Ermittelt oder definiert die Auflistung von benutzerdefinierten Regeln.</span><span class="sxs-lookup"><span data-stu-id="e11f4-107">Gets or sets collection of custom security rules.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>