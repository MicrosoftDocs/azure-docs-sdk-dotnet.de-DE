<Type Name="BlobStreamInputDataSource" FullName="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource">
  <TypeSignature Language="C#" Value="public class BlobStreamInputDataSource : Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BlobStreamInputDataSource extends Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource" />
  <TypeSignature Language="VB.NET" Value="Public Class BlobStreamInputDataSource&#xA;Inherits StreamInputDataSource" />
  <TypeSignature Language="F#" Value="type BlobStreamInputDataSource = class&#xA;    inherit StreamInputDataSource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StreamAnalytics.Models.StreamInputDataSource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Microsoft.Storage/Blob")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Beschreibt eine Eingabe Blob-Datenquelle, die datenstromdaten enthält.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobStreamInputDataSource ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der BlobStreamInputDataSource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BlobStreamInputDataSource (System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; storageAccounts = null, string container = null, string pathPattern = null, string dateFormat = null, string timeFormat = null, Nullable&lt;int&gt; sourcePartitionCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; storageAccounts, string container, string pathPattern, string dateFormat, string timeFormat, valuetype System.Nullable`1&lt;int32&gt; sourcePartitionCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.#ctor(System.Collections.Generic.IList{Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount},System.String,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional storageAccounts As IList(Of StorageAccount) = null, Optional container As String = null, Optional pathPattern As String = null, Optional dateFormat As String = null, Optional timeFormat As String = null, Optional sourcePartitionCount As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; * string * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource" Usage="new Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource (storageAccounts, container, pathPattern, dateFormat, timeFormat, sourcePartitionCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt;" />
        <Parameter Name="container" Type="System.String" />
        <Parameter Name="pathPattern" Type="System.String" />
        <Parameter Name="dateFormat" Type="System.String" />
        <Parameter Name="timeFormat" Type="System.String" />
        <Parameter Name="sourcePartitionCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="storageAccounts">Eine Liste mit mindestens ein Azure-Speicherkonten. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <param name="container">Der Name eines Containers im zugeordneten Speicherkonto an. Dieser Container enthält entweder die gehörte aus gelesen oder geschrieben werden sollen. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.</param>
        <param name="pathPattern">Das Muster für den Blob-Pfad. Regulärer Ausdruck. Er stellt ein Muster mit dem Blob Namen gesucht werden soll, um zu bestimmen, und zwar unabhängig davon, ob sie als Eingabe oder Ausgabe für den Auftrag eingeschlossen werden sollen. Finden Sie unter https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input oder https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output für eine ausführlichere Erläuterung und ein Beispiel.</param>
        <param name="dateFormat">Das Datumsformat. Wenn {Date} in der PathPattern angezeigt wird, ist der Wert dieser Eigenschaft als Datumsformat verwendet.</param>
        <param name="timeFormat">Das Zeitformat. Wenn {Time} in der PathPattern angezeigt wird, ist der Wert dieser Eigenschaft als Uhrzeitformat verwendet.</param>
        <param name="sourcePartitionCount">Die Anzahl der Partitionen von der Eingabedatenquelle Blob. Im Bereich 1-256.</param>
        <summary>
            Initialisiert eine neue Instanz der BlobStreamInputDataSource-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Container">
      <MemberSignature Language="C#" Value="public string Container { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Container" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.Container" />
      <MemberSignature Language="VB.NET" Value="Public Property Container As String" />
      <MemberSignature Language="F#" Value="member this.Container : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.Container" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.container")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen eines Containers im zugeordneten Speicherkonto an. Dieser Container enthält entweder die gehörte aus gelesen oder geschrieben werden sollen. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DateFormat">
      <MemberSignature Language="C#" Value="public string DateFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DateFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.DateFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property DateFormat As String" />
      <MemberSignature Language="F#" Value="member this.DateFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.DateFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dateFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Datumsformat. Wenn {Date} in der PathPattern angezeigt wird, ist der Wert dieser Eigenschaft als Datumsformat verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PathPattern">
      <MemberSignature Language="C#" Value="public string PathPattern { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PathPattern" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.PathPattern" />
      <MemberSignature Language="VB.NET" Value="Public Property PathPattern As String" />
      <MemberSignature Language="F#" Value="member this.PathPattern : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.PathPattern" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.pathPattern")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Blob-Pfad-Muster. Regulärer Ausdruck. Er stellt ein Muster mit dem Blob Namen gesucht werden soll, um zu bestimmen, und zwar unabhängig davon, ob sie als Eingabe oder Ausgabe für den Auftrag eingeschlossen werden sollen. Finden Sie unter https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-input oder https://docs.microsoft.com/en-us/rest/api/streamanalytics/stream-analytics-output für eine ausführlichere Erläuterung und ein Beispiel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourcePartitionCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SourcePartitionCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SourcePartitionCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.SourcePartitionCount" />
      <MemberSignature Language="VB.NET" Value="Public Property SourcePartitionCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SourcePartitionCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.SourcePartitionCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sourcePartitionCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Partitionen von der Eingabedatenquelle Blob.
            Im Bereich 1-256.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; StorageAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; StorageAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.StorageAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageAccounts As IList(Of StorageAccount)" />
      <MemberSignature Language="F#" Value="member this.StorageAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt; with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.StorageAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.storageAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StreamAnalytics.Models.StorageAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste von einem oder mehreren Azure-Speicher-Konten. Auf (CreateOrReplace)-PUT-Anforderungen erforderlich.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeFormat">
      <MemberSignature Language="C#" Value="public string TimeFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TimeFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.TimeFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property TimeFormat As String" />
      <MemberSignature Language="F#" Value="member this.TimeFormat : string with get, set" Usage="Microsoft.Azure.Management.StreamAnalytics.Models.BlobStreamInputDataSource.TimeFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StreamAnalytics</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.timeFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Zeitformat. Wenn {Time} in der PathPattern angezeigt wird, ist der Wert dieser Eigenschaft als Uhrzeitformat verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>