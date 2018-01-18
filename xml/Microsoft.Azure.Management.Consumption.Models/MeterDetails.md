<Type Name="MeterDetails" FullName="Microsoft.Azure.Management.Consumption.Models.MeterDetails">
  <TypeSignature Language="C#" Value="public class MeterDetails" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MeterDetails extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Consumption.Models.MeterDetails" />
  <TypeSignature Language="VB.NET" Value="Public Class MeterDetails" />
  <TypeSignature Language="F#" Value="type MeterDetails = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="65639-101">Die Eigenschaften des Messgeräts Details.</span><span class="sxs-lookup"><span data-stu-id="65639-101">The properties of the meter detail.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MeterDetails ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.Models.MeterDetails.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="65639-102">Initialisiert eine neue Instanz der MeterDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="65639-102">Initializes a new instance of the MeterDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MeterDetails (string meterName = null, string meterCategory = null, string meterSubCategory = null, string unit = null, string meterLocation = null, Nullable&lt;decimal&gt; totalIncludedQuantity = null, Nullable&lt;decimal&gt; pretaxStandardRate = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string meterName, string meterCategory, string meterSubCategory, string unit, string meterLocation, valuetype System.Nullable`1&lt;valuetype System.Decimal&gt; totalIncludedQuantity, valuetype System.Nullable`1&lt;valuetype System.Decimal&gt; pretaxStandardRate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.Models.MeterDetails.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Decimal},System.Nullable{System.Decimal})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional meterName As String = null, Optional meterCategory As String = null, Optional meterSubCategory As String = null, Optional unit As String = null, Optional meterLocation As String = null, Optional totalIncludedQuantity As Nullable(Of Decimal) = null, Optional pretaxStandardRate As Nullable(Of Decimal) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Consumption.Models.MeterDetails : string * string * string * string * string * Nullable&lt;decimal&gt; * Nullable&lt;decimal&gt; -&gt; Microsoft.Azure.Management.Consumption.Models.MeterDetails" Usage="new Microsoft.Azure.Management.Consumption.Models.MeterDetails (meterName, meterCategory, meterSubCategory, unit, meterLocation, totalIncludedQuantity, pretaxStandardRate)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="meterName" Type="System.String" />
        <Parameter Name="meterCategory" Type="System.String" />
        <Parameter Name="meterSubCategory" Type="System.String" />
        <Parameter Name="unit" Type="System.String" />
        <Parameter Name="meterLocation" Type="System.String" />
        <Parameter Name="totalIncludedQuantity" Type="System.Nullable&lt;System.Decimal&gt;" />
        <Parameter Name="pretaxStandardRate" Type="System.Nullable&lt;System.Decimal&gt;" />
      </Parameters>
      <Docs>
        <param name="meterName"><span data-ttu-id="65639-103">Der Name des Messgeräts, in der angegebenen Messgerät-Kategorie</span><span class="sxs-lookup"><span data-stu-id="65639-103">The name of the meter, within the given meter category</span></span></param>
        <param name="meterCategory"><span data-ttu-id="65639-104">Die Kategorie des Messgeräts, z. B. "Cloud Services", "Netzwerk", etc...</span><span class="sxs-lookup"><span data-stu-id="65639-104">The category of the meter, for example, 'Cloud services', 'Networking', etc..</span></span></param>
        <param name="meterSubCategory"><span data-ttu-id="65639-105">Die Unterkategorie des Messgeräts, z. B. "A6 Cloud Services", "ExpressRoute (IXP)", etc...</span><span class="sxs-lookup"><span data-stu-id="65639-105">The subcategory of the meter, for example, 'A6 Cloud services', 'ExpressRoute (IXP)', etc..</span></span></param>
        <param name="unit"><span data-ttu-id="65639-106">Die Einheit, in der die Nutzung des Messgeräts, in Rechnung z. B., "Stunden", "GB" usw. gestellten.</span><span class="sxs-lookup"><span data-stu-id="65639-106">The unit in which the meter consumption is charged, for example, 'Hours', 'GB', etc.</span></span></param>
        <param name="meterLocation"><span data-ttu-id="65639-107">Der Speicherort, in dem der Azure-Dienst verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="65639-107">The location in which the Azure service is available.</span></span></param>
        <param name="totalIncludedQuantity"><span data-ttu-id="65639-108">Die Summe enthalten die Menge, die das Angebot zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="65639-108">The total included quantity associated with the offer.</span></span></param>
        <param name="pretaxStandardRate"><span data-ttu-id="65639-109">Der Preis gewöhnlichen auflisten.</span><span class="sxs-lookup"><span data-stu-id="65639-109">The pretax listing price.</span></span></param>
        <summary>
            <span data-ttu-id="65639-110">Initialisiert eine neue Instanz der MeterDetails-Klasse.</span><span class="sxs-lookup"><span data-stu-id="65639-110">Initializes a new instance of the MeterDetails class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MeterCategory">
      <MemberSignature Language="C#" Value="public string MeterCategory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MeterCategory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.MeterDetails.MeterCategory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MeterCategory As String" />
      <MemberSignature Language="F#" Value="member this.MeterCategory : string" Usage="Microsoft.Azure.Management.Consumption.Models.MeterDetails.MeterCategory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="meterCategory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="65639-111">Ruft die Kategorie des Messgeräts, z. B. "Cloud Services", "Netzwerk", etc...</span><span class="sxs-lookup"><span data-stu-id="65639-111">Gets the category of the meter, for example, 'Cloud services', 'Networking', etc..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MeterLocation">
      <MemberSignature Language="C#" Value="public string MeterLocation { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MeterLocation" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.MeterDetails.MeterLocation" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MeterLocation As String" />
      <MemberSignature Language="F#" Value="member this.MeterLocation : string" Usage="Microsoft.Azure.Management.Consumption.Models.MeterDetails.MeterLocation" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="meterLocation")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="65639-112">Ruft den Speicherort, in dem der Azure-Dienst verfügbar ist.</span><span class="sxs-lookup"><span data-stu-id="65639-112">Gets the location in which the Azure service is available.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MeterName">
      <MemberSignature Language="C#" Value="public string MeterName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MeterName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.MeterDetails.MeterName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MeterName As String" />
      <MemberSignature Language="F#" Value="member this.MeterName : string" Usage="Microsoft.Azure.Management.Consumption.Models.MeterDetails.MeterName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="meterName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="65639-113">Ruft den Namen des Messgeräts, in der angegebenen Messgerät-Kategorie</span><span class="sxs-lookup"><span data-stu-id="65639-113">Gets the name of the meter, within the given meter category</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MeterSubCategory">
      <MemberSignature Language="C#" Value="public string MeterSubCategory { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MeterSubCategory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.MeterDetails.MeterSubCategory" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MeterSubCategory As String" />
      <MemberSignature Language="F#" Value="member this.MeterSubCategory : string" Usage="Microsoft.Azure.Management.Consumption.Models.MeterDetails.MeterSubCategory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="meterSubCategory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="65639-114">Ruft die Unterkategorie des Messgeräts, z. B. "A6 Cloud Services", "ExpressRoute (IXP)", etc...</span><span class="sxs-lookup"><span data-stu-id="65639-114">Gets the subcategory of the meter, for example, 'A6 Cloud services', 'ExpressRoute (IXP)', etc..</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PretaxStandardRate">
      <MemberSignature Language="C#" Value="public Nullable&lt;decimal&gt; PretaxStandardRate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Decimal&gt; PretaxStandardRate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.MeterDetails.PretaxStandardRate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PretaxStandardRate As Nullable(Of Decimal)" />
      <MemberSignature Language="F#" Value="member this.PretaxStandardRate : Nullable&lt;decimal&gt;" Usage="Microsoft.Azure.Management.Consumption.Models.MeterDetails.PretaxStandardRate" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="pretaxStandardRate")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Decimal&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="65639-115">Ruft den Preis gewöhnlichen Auflistung ab.</span><span class="sxs-lookup"><span data-stu-id="65639-115">Gets the pretax listing price.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalIncludedQuantity">
      <MemberSignature Language="C#" Value="public Nullable&lt;decimal&gt; TotalIncludedQuantity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.Decimal&gt; TotalIncludedQuantity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.MeterDetails.TotalIncludedQuantity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TotalIncludedQuantity As Nullable(Of Decimal)" />
      <MemberSignature Language="F#" Value="member this.TotalIncludedQuantity : Nullable&lt;decimal&gt;" Usage="Microsoft.Azure.Management.Consumption.Models.MeterDetails.TotalIncludedQuantity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalIncludedQuantity")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Decimal&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="65639-116">Ruft die Gesamtmenge der enthalten das Angebot zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="65639-116">Gets the total included quantity associated with the offer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unit">
      <MemberSignature Language="C#" Value="public string Unit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Unit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Consumption.Models.MeterDetails.Unit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Unit As String" />
      <MemberSignature Language="F#" Value="member this.Unit : string" Usage="Microsoft.Azure.Management.Consumption.Models.MeterDetails.Unit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="unit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="65639-117">Ruft die Einheit, in der die Nutzung des Messgeräts, in Rechnung z. B., "Stunden", "GB" usw. gestellten, ab.</span><span class="sxs-lookup"><span data-stu-id="65639-117">Gets the unit in which the meter consumption is charged, for example, 'Hours', 'GB', etc.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>