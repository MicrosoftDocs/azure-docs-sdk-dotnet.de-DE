<Type Name="OSDisk" FullName="Microsoft.Azure.Batch.Protocol.Models.OSDisk">
  <TypeSignature Language="C#" Value="public class OSDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OSDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.OSDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class OSDisk" />
  <TypeSignature Language="F#" Value="type OSDisk = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="107ac-101">Einstellungen für den Betriebssystemdatenträger des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="107ac-101">Settings for the operating system disk of the virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OSDisk.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="107ac-102">Initialisiert eine neue Instanz der Betriebssystemdatenträger-Klasse.</span><span class="sxs-lookup"><span data-stu-id="107ac-102">Initializes a new instance of the OSDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDisk (Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; caching = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; caching) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.OSDisk.#ctor(System.Nullable{Microsoft.Azure.Batch.Protocol.Models.CachingType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional caching As Nullable(Of CachingType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.OSDisk : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.OSDisk" Usage="new Microsoft.Azure.Batch.Protocol.Models.OSDisk caching" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt;" />
      </Parameters>
      <Docs>
        <param name="caching"><span data-ttu-id="107ac-103">Der Typ des Zwischenspeichern konfigurieren, um für den Betriebssystem-Datenträger zu aktivieren.</span><span class="sxs-lookup"><span data-stu-id="107ac-103">The type of caching to enable for the OS disk.</span></span></param>
        <summary>
            <span data-ttu-id="107ac-104">Initialisiert eine neue Instanz der Betriebssystemdatenträger-Klasse.</span><span class="sxs-lookup"><span data-stu-id="107ac-104">Initializes a new instance of the OSDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.OSDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingType)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.OSDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caching")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CachingType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="107ac-105">Ruft ab oder legt den Typ des caching zum Aktivieren der für den Betriebssystem-Datenträger.</span><span class="sxs-lookup"><span data-stu-id="107ac-105">Gets or sets the type of caching to enable for the OS disk.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="107ac-106">Der Standardwert für das caching ist none.</span><span class="sxs-lookup"><span data-stu-id="107ac-106">The default value for caching is none.</span></span> <span data-ttu-id="107ac-107">Weitere Informationen zu Optionen für die Zwischenspeicherung finden Sie unter: https://blogs.msdn.microsoft.com/windowsazurestorage/2012/06/27/exploring-windows-azure-drives-disks-and-images/.</span><span class="sxs-lookup"><span data-stu-id="107ac-107">For information about the caching options see: https://blogs.msdn.microsoft.com/windowsazurestorage/2012/06/27/exploring-windows-azure-drives-disks-and-images/.</span></span>
            <span data-ttu-id="107ac-108">Folgende Werte sind möglich: "none", "ReadOnly", "ReadWrite"</span><span class="sxs-lookup"><span data-stu-id="107ac-108">Possible values include: 'none', 'readOnly', 'readWrite'</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>