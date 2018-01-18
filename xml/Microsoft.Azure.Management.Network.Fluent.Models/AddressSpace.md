<Type Name="AddressSpace" FullName="Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace">
  <TypeSignature Language="C#" Value="public class AddressSpace" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AddressSpace extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace" />
  <TypeSignature Language="VB.NET" Value="Public Class AddressSpace" />
  <TypeSignature Language="F#" Value="type AddressSpace = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9a59c-101">AddressSpace enthält ein Array von IP-Adressbereiche, die von den Subnetzen des virtuellen Netzwerks verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="9a59c-101">AddressSpace contains an array of IP address ranges that can be used by subnets of the virtual network.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AddressSpace ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9a59c-102">Initialisiert eine neue Instanz der AddressSpace-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9a59c-102">Initializes a new instance of the AddressSpace class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AddressSpace (System.Collections.Generic.IList&lt;string&gt; addressPrefixes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;string&gt; addressPrefixes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace.#ctor(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional addressPrefixes As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace addressPrefixes" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="addressPrefixes" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="addressPrefixes"><span data-ttu-id="9a59c-103">Eine Liste der für dieses virtuelle Netzwerk im CIDR-Notation reservierten Adressblöcke.</span><span class="sxs-lookup"><span data-stu-id="9a59c-103">A list of address blocks reserved for this virtual network in CIDR notation.</span></span></param>
        <summary>
            <span data-ttu-id="9a59c-104">Initialisiert eine neue Instanz der AddressSpace-Klasse.</span><span class="sxs-lookup"><span data-stu-id="9a59c-104">Initializes a new instance of the AddressSpace class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddressPrefixes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AddressPrefixes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AddressPrefixes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace.AddressPrefixes" />
      <MemberSignature Language="VB.NET" Value="Public Property AddressPrefixes As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AddressPrefixes : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.AddressSpace.AddressPrefixes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="addressPrefixes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9a59c-105">Ruft ab, oder eine Liste von-Adressblöcke in CIDR-Notation für dieses virtuelle Netzwerk reservierten fest.</span><span class="sxs-lookup"><span data-stu-id="9a59c-105">Gets or sets a list of address blocks reserved for this virtual network in CIDR notation.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>