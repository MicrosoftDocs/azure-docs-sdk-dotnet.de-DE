<Type Name="RecommendedElasticPoolMetric" FullName="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric">
  <TypeSignature Language="C#" Value="public class RecommendedElasticPoolMetric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RecommendedElasticPoolMetric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric" />
  <TypeSignature Language="VB.NET" Value="Public Class RecommendedElasticPoolMetric" />
  <TypeSignature Language="F#" Value="type RecommendedElasticPoolMetric = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="33ef7-101">Stellt empfohlene elastischen Pool Metrik.</span><span class="sxs-lookup"><span data-stu-id="33ef7-101">Represents recommended elastic pool metric.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedElasticPoolMetric ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="33ef7-102">Initialisiert eine neue Instanz der RecommendedElasticPoolMetric-Klasse.</span><span class="sxs-lookup"><span data-stu-id="33ef7-102">Initializes a new instance of the RecommendedElasticPoolMetric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RecommendedElasticPoolMetric (Nullable&lt;DateTime&gt; dateTime = null, Nullable&lt;double&gt; dtu = null, Nullable&lt;double&gt; sizeGB = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; dateTime, valuetype System.Nullable`1&lt;float64&gt; dtu, valuetype System.Nullable`1&lt;float64&gt; sizeGB) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.#ctor(System.Nullable{System.DateTime},System.Nullable{System.Double},System.Nullable{System.Double})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional dateTime As Nullable(Of DateTime) = null, Optional dtu As Nullable(Of Double) = null, Optional sizeGB As Nullable(Of Double) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric : Nullable&lt;DateTime&gt; * Nullable&lt;double&gt; * Nullable&lt;double&gt; -&gt; Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric" Usage="new Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric (dateTime, dtu, sizeGB)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="dateTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="dtu" Type="System.Nullable&lt;System.Double&gt;" />
        <Parameter Name="sizeGB" Type="System.Nullable&lt;System.Double&gt;" />
      </Parameters>
      <Docs>
        <param name="dateTime"><span data-ttu-id="33ef7-103">Der Zeitpunkt der Metrik (ISO8601-Format).</span><span class="sxs-lookup"><span data-stu-id="33ef7-103">The time of metric (ISO8601 format).</span></span></param>
        <param name="dtu"><span data-ttu-id="33ef7-104">Ruft ab oder legt die dtu-Anzahl (Datenbanktransaktionseinheiten).</span><span class="sxs-lookup"><span data-stu-id="33ef7-104">Gets or sets the DTUs (Database Transaction Units).</span></span> <span data-ttu-id="33ef7-105">Weitere Informationen finden Sie https://azure.microsoft.com/documentation/articles/sql-database-what-is-a-dtu/</span><span class="sxs-lookup"><span data-stu-id="33ef7-105">See https://azure.microsoft.com/documentation/articles/sql-database-what-is-a-dtu/</span></span></param>
        <param name="sizeGB"><span data-ttu-id="33ef7-106">Ruft ab oder legt die Größe in Gigabyte fest.</span><span class="sxs-lookup"><span data-stu-id="33ef7-106">Gets or sets size in gigabytes.</span></span></param>
        <summary>
            <span data-ttu-id="33ef7-107">Initialisiert eine neue Instanz der RecommendedElasticPoolMetric-Klasse.</span><span class="sxs-lookup"><span data-stu-id="33ef7-107">Initializes a new instance of the RecommendedElasticPoolMetric class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DateTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; DateTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; DateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.DateTime" />
      <MemberSignature Language="VB.NET" Value="Public Property DateTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.DateTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.DateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dateTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33ef7-108">Ruft ab oder legt die Zeit der Metrik (ISO8601-Format) fest.</span><span class="sxs-lookup"><span data-stu-id="33ef7-108">Gets or sets the time of metric (ISO8601 format).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dtu">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; Dtu { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; Dtu" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.Dtu" />
      <MemberSignature Language="VB.NET" Value="Public Property Dtu As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.Dtu : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.Dtu" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="dtu")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33ef7-109">Ruft ab oder legt die dtu-Anzahl (Datenbanktransaktionseinheiten).</span><span class="sxs-lookup"><span data-stu-id="33ef7-109">Gets or sets the DTUs (Database Transaction Units).</span></span> <span data-ttu-id="33ef7-110">Weitere Informationen finden Sie https://azure.microsoft.com/documentation/articles/sql-database-what-is-a-dtu/</span><span class="sxs-lookup"><span data-stu-id="33ef7-110">See https://azure.microsoft.com/documentation/articles/sql-database-what-is-a-dtu/</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeGB">
      <MemberSignature Language="C#" Value="public Nullable&lt;double&gt; SizeGB { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;float64&gt; SizeGB" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.SizeGB" />
      <MemberSignature Language="VB.NET" Value="Public Property SizeGB As Nullable(Of Double)" />
      <MemberSignature Language="F#" Value="member this.SizeGB : Nullable&lt;double&gt; with get, set" Usage="Microsoft.Azure.Management.Sql.Models.RecommendedElasticPoolMetric.SizeGB" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sizeGB")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Double&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="33ef7-111">Ruft ab oder legt die Größe in Gigabyte fest.</span><span class="sxs-lookup"><span data-stu-id="33ef7-111">Gets or sets size in gigabytes.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>