<Type Name="SecurityGroupViewResult" FullName="Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult">
  <TypeSignature Language="C#" Value="public class SecurityGroupViewResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecurityGroupViewResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult" />
  <TypeSignature Language="VB.NET" Value="Public Class SecurityGroupViewResult" />
  <TypeSignature Language="F#" Value="type SecurityGroupViewResult = class" />
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
            <span data-ttu-id="15a75-101">Die Informationen zu Sicherheitsregeln auf den angegebenen virtuellen Computer angewendet.</span><span class="sxs-lookup"><span data-stu-id="15a75-101">The information about security rules applied to the specified VM.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityGroupViewResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult.#ctor" />
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
            <span data-ttu-id="15a75-102">Initialisiert eine neue Instanz der SecurityGroupViewResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="15a75-102">Initializes a new instance of the SecurityGroupViewResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityGroupViewResult (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt; networkInterfaces = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt; networkInterfaces) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional networkInterfaces As IList(Of SecurityGroupNetworkInterface) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt; -&gt; Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult" Usage="new Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult networkInterfaces" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="networkInterfaces" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt;" />
      </Parameters>
      <Docs>
        <param name="networkInterfaces"><span data-ttu-id="15a75-103">Liste der Netzwerkschnittstellen auf dem angegebenen virtuellen Computer.</span><span class="sxs-lookup"><span data-stu-id="15a75-103">List of network interfaces on the specified VM.</span></span></param>
        <summary>
            <span data-ttu-id="15a75-104">Initialisiert eine neue Instanz der SecurityGroupViewResult-Klasse.</span><span class="sxs-lookup"><span data-stu-id="15a75-104">Initializes a new instance of the SecurityGroupViewResult class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterfaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt; NetworkInterfaces { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt; NetworkInterfaces" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult.NetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterfaces As IList(Of SecurityGroupNetworkInterface)" />
      <MemberSignature Language="F#" Value="member this.NetworkInterfaces : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityGroupViewResult.NetworkInterfaces" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkInterfaces")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="15a75-105">Ruft ab oder legt die Liste der Netzwerkschnittstellen auf dem angegebenen virtuellen Computer fest.</span><span class="sxs-lookup"><span data-stu-id="15a75-105">Gets or sets list of network interfaces on the specified VM.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>