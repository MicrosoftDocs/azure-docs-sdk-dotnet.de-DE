<Type Name="USqlDistributionInfo" FullName="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo">
  <TypeSignature Language="C#" Value="public class USqlDistributionInfo" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit USqlDistributionInfo extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo" />
  <TypeSignature Language="VB.NET" Value="Public Class USqlDistributionInfo" />
  <TypeSignature Language="F#" Value="type USqlDistributionInfo = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3e7f0-101">Ein Data Lake Analytics-Katalog U-SQL-Informationen Verteilungsobjekt.</span><span class="sxs-lookup"><span data-stu-id="3e7f0-101">A Data Lake Analytics catalog U-SQL distribution information object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlDistributionInfo ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3e7f0-102">Initialisiert eine neue Instanz der USqlDistributionInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3e7f0-102">Initializes a new instance of the USqlDistributionInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public USqlDistributionInfo (Nullable&lt;int&gt; type = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; keys = null, Nullable&lt;int&gt; count = null, Nullable&lt;int&gt; dynamicCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; type, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; keys, valuetype System.Nullable`1&lt;int32&gt; count, valuetype System.Nullable`1&lt;int32&gt; dynamicCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.#ctor(System.Nullable{System.Int32},System.Collections.Generic.IList{Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn},System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional type As Nullable(Of Integer) = null, Optional keys As IList(Of USqlDirectedColumn) = null, Optional count As Nullable(Of Integer) = null, Optional dynamicCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo : Nullable&lt;int&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo" Usage="new Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo (type, keys, count, dynamicCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="type" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="keys" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt;" />
        <Parameter Name="count" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="dynamicCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="type"><span data-ttu-id="3e7f0-103">Der Typ des diesem Verteilungspunkt.</span><span class="sxs-lookup"><span data-stu-id="3e7f0-103">the type of this distribution.</span></span></param>
        <param name="keys"><span data-ttu-id="3e7f0-104">die Liste der gesteuerte Spalten in der Verteilung</span><span class="sxs-lookup"><span data-stu-id="3e7f0-104">the list of directed columns in the distribution</span></span></param>
        <param name="count"><span data-ttu-id="3e7f0-105">die Anzahl der Indizes, die mit diesem Verteilungspunkt.</span><span class="sxs-lookup"><span data-stu-id="3e7f0-105">the count of indices using this distribution.</span></span></param>
        <param name="dynamicCount"><span data-ttu-id="3e7f0-106">die dynamische Anzahl von Indizes, die mit diesem Verteilungspunkt.</span><span class="sxs-lookup"><span data-stu-id="3e7f0-106">the dynamic count of indices using this distribution.</span></span></param>
        <summary>
            <span data-ttu-id="3e7f0-107">Initialisiert eine neue Instanz der USqlDistributionInfo-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3e7f0-107">Initializes a new instance of the USqlDistributionInfo class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Count">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Count { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Count" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.Count" />
      <MemberSignature Language="VB.NET" Value="Public Property Count As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Count : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.Count" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="count")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e7f0-108">Ruft ab oder legt die Anzahl der Indizes, die mit diesem Verteilungspunkt.</span><span class="sxs-lookup"><span data-stu-id="3e7f0-108">Gets or sets the count of indices using this distribution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DynamicCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DynamicCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DynamicCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.DynamicCount" />
      <MemberSignature Language="VB.NET" Value="Public Property DynamicCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DynamicCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.DynamicCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dynamicCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e7f0-109">Ermittelt oder definiert die dynamische Anzahl der Indizes, die mit diesem Verteilungspunkt.</span><span class="sxs-lookup"><span data-stu-id="3e7f0-109">Gets or sets the dynamic count of indices using this distribution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Keys">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; Keys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; Keys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.Keys" />
      <MemberSignature Language="VB.NET" Value="Public Property Keys As IList(Of USqlDirectedColumn)" />
      <MemberSignature Language="F#" Value="member this.Keys : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.Keys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="keys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDirectedColumn&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e7f0-110">Ruft ab oder legt die Liste der gesteuerte Spalten in der Verteilung</span><span class="sxs-lookup"><span data-stu-id="3e7f0-110">Gets or sets the list of directed columns in the distribution</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Type { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.Type" />
      <MemberSignature Language="VB.NET" Value="Public Property Type As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Type : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.DataLake.Analytics.Models.USqlDistributionInfo.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Analytics</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="type")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e7f0-111">Ruft ab oder legt den Typ von diesem Verteilungspunkt fest.</span><span class="sxs-lookup"><span data-stu-id="3e7f0-111">Gets or sets the type of this distribution.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>