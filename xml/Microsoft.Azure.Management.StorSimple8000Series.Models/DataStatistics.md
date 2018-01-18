<Type Name="DataStatistics" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics">
  <TypeSignature Language="C#" Value="public class DataStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DataStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class DataStatistics" />
  <TypeSignature Language="F#" Value="type DataStatistics = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="94b5e-101">Zusätzliche Details im Zusammenhang mit den Daten verwandter Statistiken eines Auftrags.</span><span class="sxs-lookup"><span data-stu-id="94b5e-101">The additional details related to the data related statistics of a job.</span></span>
            <span data-ttu-id="94b5e-102">Derzeit gilt nur für Sicherungs-, Klon- und Wiederherstellungsaufträgen.</span><span class="sxs-lookup"><span data-stu-id="94b5e-102">Currently applicable only for Backup, Clone and Restore jobs.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataStatistics ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="94b5e-103">Initialisiert eine neue Instanz der DataStatistics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="94b5e-103">Initializes a new instance of the DataStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DataStatistics (Nullable&lt;long&gt; totalData = null, Nullable&lt;long&gt; processedData = null, Nullable&lt;long&gt; cloudData = null, Nullable&lt;long&gt; throughput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int64&gt; totalData, valuetype System.Nullable`1&lt;int64&gt; processedData, valuetype System.Nullable`1&lt;int64&gt; cloudData, valuetype System.Nullable`1&lt;int64&gt; throughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.#ctor(System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64},System.Nullable{System.Int64})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional totalData As Nullable(Of Long) = null, Optional processedData As Nullable(Of Long) = null, Optional cloudData As Nullable(Of Long) = null, Optional throughput As Nullable(Of Long) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics : Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; * Nullable&lt;int64&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics (totalData, processedData, cloudData, throughput)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="totalData" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="processedData" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="cloudData" Type="System.Nullable&lt;System.Int64&gt;" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int64&gt;" />
      </Parameters>
      <Docs>
        <param name="totalData"><span data-ttu-id="94b5e-104">Die Gesamtanzahl der Bytes der Daten, die als Teil des Auftrags verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="94b5e-104">The total bytes of data to be processed, as part of the job.</span></span></param>
        <param name="processedData"><span data-ttu-id="94b5e-105">Die Anzahl der Bytes der Daten, die bis jetzt als Teil des Auftrags verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="94b5e-105">The number of bytes of data processed till now, as part of the job.</span></span></param>
        <param name="cloudData"><span data-ttu-id="94b5e-106">Die Anzahl der Bytes an Daten in der cloud als Teil des Auftrags geschrieben werden soll.</span><span class="sxs-lookup"><span data-stu-id="94b5e-106">The number of bytes of data written to cloud, as part of the job.</span></span></param>
        <param name="throughput"><span data-ttu-id="94b5e-107">Der durchschnittliche Durchsatz des Daten-processed(bytes/sec) als Teil des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="94b5e-107">The average throughput of data processed(bytes/sec), as part of the job.</span></span></param>
        <summary>
            <span data-ttu-id="94b5e-108">Initialisiert eine neue Instanz der DataStatistics-Klasse.</span><span class="sxs-lookup"><span data-stu-id="94b5e-108">Initializes a new instance of the DataStatistics class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloudData">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; CloudData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; CloudData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.CloudData" />
      <MemberSignature Language="VB.NET" Value="Public Property CloudData As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.CloudData : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.CloudData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="cloudData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94b5e-109">Ruft ab oder legt die Anzahl der Bytes an Daten in der cloud als Teil des Auftrags geschrieben.</span><span class="sxs-lookup"><span data-stu-id="94b5e-109">Gets or sets the number of bytes of data written to cloud, as part of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProcessedData">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; ProcessedData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; ProcessedData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.ProcessedData" />
      <MemberSignature Language="VB.NET" Value="Public Property ProcessedData As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.ProcessedData : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.ProcessedData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="processedData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94b5e-110">Ruft ab oder legt die Anzahl der Bytes der Daten, die bis jetzt als Teil des Auftrags verarbeitet.</span><span class="sxs-lookup"><span data-stu-id="94b5e-110">Gets or sets the number of bytes of data processed till now, as part of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Throughput">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; Throughput { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; Throughput" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.Throughput" />
      <MemberSignature Language="VB.NET" Value="Public Property Throughput As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.Throughput : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.Throughput" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="throughput")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94b5e-111">Abrufen oder festlegen den durchschnittlichen Durchsatz des Daten-processed(bytes/sec) als Teil des Auftrags.</span><span class="sxs-lookup"><span data-stu-id="94b5e-111">Gets or sets the average throughput of data processed(bytes/sec), as part of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TotalData">
      <MemberSignature Language="C#" Value="public Nullable&lt;long&gt; TotalData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int64&gt; TotalData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.TotalData" />
      <MemberSignature Language="VB.NET" Value="Public Property TotalData As Nullable(Of Long)" />
      <MemberSignature Language="F#" Value="member this.TotalData : Nullable&lt;int64&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.DataStatistics.TotalData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="totalData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="94b5e-112">Ruft ab oder legt die Gesamtanzahl der Bytes der Daten, die als Teil des Auftrags verarbeitet werden.</span><span class="sxs-lookup"><span data-stu-id="94b5e-112">Gets or sets the total bytes of data to be processed, as part of the job.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>