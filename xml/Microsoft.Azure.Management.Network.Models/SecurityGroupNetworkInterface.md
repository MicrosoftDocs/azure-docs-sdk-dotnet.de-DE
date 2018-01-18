<Type Name="SecurityGroupNetworkInterface" FullName="Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface">
  <TypeSignature Language="C#" Value="public class SecurityGroupNetworkInterface" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SecurityGroupNetworkInterface extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface" />
  <TypeSignature Language="VB.NET" Value="Public Class SecurityGroupNetworkInterface" />
  <TypeSignature Language="F#" Value="type SecurityGroupNetworkInterface = class" />
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
            <span data-ttu-id="5a4c8-101">Die Netzwerkschnittstelle und seine zugehörigen Sicherheitsregeln.</span><span class="sxs-lookup"><span data-stu-id="5a4c8-101">Network interface and all its associated security rules.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityGroupNetworkInterface ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface.#ctor" />
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
            <span data-ttu-id="5a4c8-102">Initialisiert eine neue Instanz der SecurityGroupNetworkInterface-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5a4c8-102">Initializes a new instance of the SecurityGroupNetworkInterface class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SecurityGroupNetworkInterface (string id = null, Microsoft.Azure.Management.Network.Models.SecurityRuleAssociations securityRuleAssociations = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class Microsoft.Azure.Management.Network.Models.SecurityRuleAssociations securityRuleAssociations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface.#ctor(System.String,Microsoft.Azure.Management.Network.Models.SecurityRuleAssociations)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface : string * Microsoft.Azure.Management.Network.Models.SecurityRuleAssociations -&gt; Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface" Usage="new Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface (id, securityRuleAssociations)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="securityRuleAssociations" Type="Microsoft.Azure.Management.Network.Models.SecurityRuleAssociations" />
      </Parameters>
      <Docs>
        <param name="id"><span data-ttu-id="5a4c8-103">Die ID der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="5a4c8-103">ID of the network interface.</span></span></param>
        <param name="securityRuleAssociations">To be added.</param>
        <summary>
            <span data-ttu-id="5a4c8-104">Initialisiert eine neue Instanz der SecurityGroupNetworkInterface-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5a4c8-104">Initializes a new instance of the SecurityGroupNetworkInterface class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface.Id" />
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
            <span data-ttu-id="5a4c8-105">Ruft ab oder legt die ID der Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="5a4c8-105">Gets or sets ID of the network interface.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecurityRuleAssociations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SecurityRuleAssociations SecurityRuleAssociations { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SecurityRuleAssociations SecurityRuleAssociations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface.SecurityRuleAssociations" />
      <MemberSignature Language="VB.NET" Value="Public Property SecurityRuleAssociations As SecurityRuleAssociations" />
      <MemberSignature Language="F#" Value="member this.SecurityRuleAssociations : Microsoft.Azure.Management.Network.Models.SecurityRuleAssociations with get, set" Usage="Microsoft.Azure.Management.Network.Models.SecurityGroupNetworkInterface.SecurityRuleAssociations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="securityRuleAssociations")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SecurityRuleAssociations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary />
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>