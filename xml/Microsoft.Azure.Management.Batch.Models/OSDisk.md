<Type Name="OSDisk" FullName="Microsoft.Azure.Management.Batch.Models.OSDisk">
  <TypeSignature Language="C#" Value="public class OSDisk" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit OSDisk extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.OSDisk" />
  <TypeSignature Language="VB.NET" Value="Public Class OSDisk" />
  <TypeSignature Language="F#" Value="type OSDisk = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="fdcc5-101">Einstellungen für den Betriebssystemdatenträger des virtuellen Computers.</span><span class="sxs-lookup"><span data-stu-id="fdcc5-101">Settings for the operating system disk of the virtual machine.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDisk ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.OSDisk.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="fdcc5-102">Initialisiert eine neue Instanz der Betriebssystemdatenträger-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fdcc5-102">Initializes a new instance of the OSDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public OSDisk (Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; caching = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CachingType&gt; caching) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.OSDisk.#ctor(System.Nullable{Microsoft.Azure.Management.Batch.Models.CachingType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional caching As Nullable(Of CachingType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.OSDisk : Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; -&gt; Microsoft.Azure.Management.Batch.Models.OSDisk" Usage="new Microsoft.Azure.Management.Batch.Models.OSDisk caching" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="caching" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt;" />
      </Parameters>
      <Docs>
        <param name="caching"><span data-ttu-id="fdcc5-103">Der Typ des Zwischenspeichern konfigurieren, um für die Datenträger für Daten aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="fdcc5-103">The type of caching to be enabled for the data disks.</span></span> <span data-ttu-id="fdcc5-104">None: den cachingmodus des Datenträgers ist nicht aktiviert.</span><span class="sxs-lookup"><span data-stu-id="fdcc5-104">none - The caching mode for the disk is not enabled.</span></span>
            <span data-ttu-id="fdcc5-105">ReadOnly - wird für der cachingmodus für den Datenträger nur gelesen werden.</span><span class="sxs-lookup"><span data-stu-id="fdcc5-105">readOnly - The caching mode for the disk is read only.</span></span> <span data-ttu-id="fdcc5-106">ReadWrite - der cachingmodus des Datenträgers gelesen und geschrieben.</span><span class="sxs-lookup"><span data-stu-id="fdcc5-106">readWrite - The caching mode for the disk is read and write.</span></span></param>
        <summary>
            <span data-ttu-id="fdcc5-107">Initialisiert eine neue Instanz der Betriebssystemdatenträger-Klasse.</span><span class="sxs-lookup"><span data-stu-id="fdcc5-107">Initializes a new instance of the OSDisk class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Caching">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; Caching { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.CachingType&gt; Caching" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.OSDisk.Caching" />
      <MemberSignature Language="VB.NET" Value="Public Property Caching As Nullable(Of CachingType)" />
      <MemberSignature Language="F#" Value="member this.Caching : Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.OSDisk.Caching" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="caching")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.CachingType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="fdcc5-108">Ruft ab oder legt den Typ des Zwischenspeichern konfigurieren, um für die Datenträger für Daten aktiviert werden.</span><span class="sxs-lookup"><span data-stu-id="fdcc5-108">Gets or sets the type of caching to be enabled for the data disks.</span></span>
            <span data-ttu-id="fdcc5-109">None: den cachingmodus des Datenträgers ist nicht aktiviert.</span><span class="sxs-lookup"><span data-stu-id="fdcc5-109">none - The caching mode for the disk is not enabled.</span></span> <span data-ttu-id="fdcc5-110">ReadOnly - wird für der cachingmodus für den Datenträger nur gelesen werden.</span><span class="sxs-lookup"><span data-stu-id="fdcc5-110">readOnly - The caching mode for the disk is read only.</span></span> <span data-ttu-id="fdcc5-111">ReadWrite - der cachingmodus des Datenträgers gelesen und geschrieben.</span><span class="sxs-lookup"><span data-stu-id="fdcc5-111">readWrite - The caching mode for the disk is read and write.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="fdcc5-112">Standardwert ist none.</span><span class="sxs-lookup"><span data-stu-id="fdcc5-112">Default value is none.</span></span> <span data-ttu-id="fdcc5-113">Folgende Werte sind möglich: "None", "ReadOnly", "ReadWrite"</span><span class="sxs-lookup"><span data-stu-id="fdcc5-113">Possible values include: 'None', 'ReadOnly', 'ReadWrite'</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>