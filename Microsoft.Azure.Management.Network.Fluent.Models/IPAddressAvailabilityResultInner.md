<Type Name="IPAddressAvailabilityResultInner" FullName="Microsoft.Azure.Management.Network.Fluent.Models.IPAddressAvailabilityResultInner">
  <TypeSignature Language="C#" Value="public class IPAddressAvailabilityResultInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IPAddressAvailabilityResultInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Models.IPAddressAvailabilityResultInner" />
  <TypeSignature Language="VB.NET" Value="Public Class IPAddressAvailabilityResultInner" />
  <TypeSignature Language="F#" Value="type IPAddressAvailabilityResultInner = class" />
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
            <span data-ttu-id="993ed-101">Antwort für CheckIPAddressAvailability-API-Aufruf</span><span class="sxs-lookup"><span data-stu-id="993ed-101">Response for CheckIPAddressAvailability API service call</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IPAddressAvailabilityResultInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.IPAddressAvailabilityResultInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="993ed-102">Initialisiert eine neue Instanz der IPAddressAvailabilityResultInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="993ed-102">Initializes a new instance of the IPAddressAvailabilityResultInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IPAddressAvailabilityResultInner (Nullable&lt;bool&gt; available = null, System.Collections.Generic.IList&lt;string&gt; availableIPAddresses = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; available, class System.Collections.Generic.IList`1&lt;string&gt; availableIPAddresses) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Models.IPAddressAvailabilityResultInner.#ctor(System.Nullable{System.Boolean},System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional available As Nullable(Of Boolean) = null, Optional availableIPAddresses As IList(Of String) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Network.Fluent.Models.IPAddressAvailabilityResultInner : Nullable&lt;bool&gt; * System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.Models.IPAddressAvailabilityResultInner" Usage="new Microsoft.Azure.Management.Network.Fluent.Models.IPAddressAvailabilityResultInner (available, availableIPAddresses)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="available" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="availableIPAddresses" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="available"><span data-ttu-id="993ed-103">Verfügbarkeit der privaten IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="993ed-103">Private IP address availability.</span></span></param>
        <param name="availableIPAddresses"><span data-ttu-id="993ed-104">Andere verfügbaren privaten IP-Adressen enthält, wenn die gestellte für Adresse verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="993ed-104">Contains other available private IP addresses if the asked for address is taken.</span></span></param>
        <summary>
            <span data-ttu-id="993ed-105">Initialisiert eine neue Instanz der IPAddressAvailabilityResultInner-Klasse.</span><span class="sxs-lookup"><span data-stu-id="993ed-105">Initializes a new instance of the IPAddressAvailabilityResultInner class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Available">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Available { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Available" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.IPAddressAvailabilityResultInner.Available" />
      <MemberSignature Language="VB.NET" Value="Public Property Available As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Available : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.IPAddressAvailabilityResultInner.Available" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="available")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="993ed-106">Ruft ab oder legt die Verfügbarkeit der privaten IP-Adresse.</span><span class="sxs-lookup"><span data-stu-id="993ed-106">Gets or sets private IP address availability.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailableIPAddresses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AvailableIPAddresses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AvailableIPAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.Models.IPAddressAvailabilityResultInner.AvailableIPAddresses" />
      <MemberSignature Language="VB.NET" Value="Public Property AvailableIPAddresses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AvailableIPAddresses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Network.Fluent.Models.IPAddressAvailabilityResultInner.AvailableIPAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="availableIPAddresses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="993ed-107">Ruft ab oder legt enthält andere verfügbaren privaten IP-Adressen auf, wenn die gestellte für Adresse verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="993ed-107">Gets or sets contains other available private IP addresses if the asked for address is taken.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>