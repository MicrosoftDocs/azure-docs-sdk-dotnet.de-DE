<Type Name="EffectiveNetworkSecurityGroupAssociation" FullName="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation">
  <TypeSignature Language="C#" Value="public class EffectiveNetworkSecurityGroupAssociation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit EffectiveNetworkSecurityGroupAssociation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation" />
  <TypeSignature Language="VB.NET" Value="Public Class EffectiveNetworkSecurityGroupAssociation" />
  <TypeSignature Language="F#" Value="type EffectiveNetworkSecurityGroupAssociation = class" />
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
            Die effektive Zuordnung zur Netzwerksicherheitsgruppe.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveNetworkSecurityGroupAssociation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation.#ctor" />
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
            Initialisiert eine neue Instanz der EffectiveNetworkSecurityGroupAssociation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public EffectiveNetworkSecurityGroupAssociation (Microsoft.Azure.Management.Network.Models.SubResource subnet = null, Microsoft.Azure.Management.Network.Models.SubResource networkInterface = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Network.Models.SubResource subnet, class Microsoft.Azure.Management.Network.Models.SubResource networkInterface) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation.#ctor(Microsoft.Azure.Management.Network.Models.SubResource,Microsoft.Azure.Management.Network.Models.SubResource)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional subnet As SubResource = null, Optional networkInterface As SubResource = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation : Microsoft.Azure.Management.Network.Models.SubResource * Microsoft.Azure.Management.Network.Models.SubResource -&gt; Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation" Usage="new Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation (subnet, networkInterface)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
        <Parameter Name="networkInterface" Type="Microsoft.Azure.Management.Network.Models.SubResource" />
      </Parameters>
      <Docs>
        <param name="subnet">Die ID des Subnetzes zugewiesen werden soll.</param>
        <param name="networkInterface">Die ID der Netzwerkschnittstelle zugewiesen werden soll.</param>
        <summary>
            Initialisiert eine neue Instanz der EffectiveNetworkSecurityGroupAssociation-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource NetworkInterface { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource NetworkInterface" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation.NetworkInterface" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkInterface As SubResource" />
      <MemberSignature Language="F#" Value="member this.NetworkInterface : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation.NetworkInterface" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="networkInterface")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID der Netzwerkschnittstelle fest, wenn zugewiesen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Models.SubResource Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Network.Models.SubResource Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As SubResource" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.Network.Models.SubResource with get, set" Usage="Microsoft.Azure.Management.Network.Models.EffectiveNetworkSecurityGroupAssociation.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network</AssemblyName>
        <AssemblyVersion>14.0.0.0</AssemblyVersion>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Models.SubResource</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID des Subnetzes fest, wenn zugewiesen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>