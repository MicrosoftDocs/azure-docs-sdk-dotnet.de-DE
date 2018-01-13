<Type Name="RoutingStorageContainerProperties" FullName="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties">
  <TypeSignature Language="C#" Value="public class RoutingStorageContainerProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit RoutingStorageContainerProperties extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class RoutingStorageContainerProperties" />
  <TypeSignature Language="F#" Value="type RoutingStorageContainerProperties = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Eigenschaften im Zusammenhang mit einem speicherendpunkt für den Container.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingStorageContainerProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der RoutingStorageContainerProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public RoutingStorageContainerProperties (string connectionString, string name, string containerName, string subscriptionId = null, string resourceGroup = null, string fileNameFormat = null, Nullable&lt;int&gt; batchFrequencyInSeconds = null, Nullable&lt;int&gt; maxChunkSizeInBytes = null, string encoding = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string connectionString, string name, string containerName, string subscriptionId, string resourceGroup, string fileNameFormat, valuetype System.Nullable`1&lt;int32&gt; batchFrequencyInSeconds, valuetype System.Nullable`1&lt;int32&gt; maxChunkSizeInBytes, string encoding) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (connectionString As String, name As String, containerName As String, Optional subscriptionId As String = null, Optional resourceGroup As String = null, Optional fileNameFormat As String = null, Optional batchFrequencyInSeconds As Nullable(Of Integer) = null, Optional maxChunkSizeInBytes As Nullable(Of Integer) = null, Optional encoding As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties : string * string * string * string * string * string * Nullable&lt;int&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties" Usage="new Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties (connectionString, name, containerName, subscriptionId, resourceGroup, fileNameFormat, batchFrequencyInSeconds, maxChunkSizeInBytes, encoding)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="subscriptionId" Type="System.String" />
        <Parameter Name="resourceGroup" Type="System.String" />
        <Parameter Name="fileNameFormat" Type="System.String" />
        <Parameter Name="batchFrequencyInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="maxChunkSizeInBytes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="encoding" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString">Die Verbindungszeichenfolge des Speicherkontos.</param>
        <param name="name">Der Name zum Identifizieren von diesem Endpunkt. Der Name kann nur alphanumerische Zeichen, Punkte, Unterstriche, Bindestriche enthalten und besitzt eine maximale Länge von 64 Zeichen lang sein. Die folgenden Namen sind reserviert: Ereignisse, OperationsMonitoringEvents, FileNotifications, $default. Endpunktnamen müssen über Endpunkttypen eindeutig sein.</param>
        <param name="containerName">Der Name des Speichercontainer im Speicherkonto.</param>
        <param name="subscriptionId">Die Abonnement-ID des Speicherkontos.</param>
        <param name="resourceGroup">Der Name der Ressourcengruppe des Speicherkontos.</param>
        <param name="fileNameFormat">Name-Dateiformat für das Blob. Standardformat lautet {Iothub} / {partition} / {JJJJ} / {MM} / {TT} / {"hh"} / {mm}. Alle Parameter müssen angegeben werden, jedoch neu angeordnet werden können.</param>
        <param name="batchFrequencyInSeconds">Das Zeitintervall mit der Blobs in den Speicher geschrieben werden. Wert muss zwischen 60 und 720 Sekunden liegen.
            Standardwert ist 300 Sekunden.</param>
        <param name="maxChunkSizeInBytes">Maximale Anzahl von Bytes für jedes Blob in den Speicher geschrieben. Wert muss zwischen 10485760(10MB) und 524288000(500MB) liegen. Standardwert ist 314572800(300MB).</param>
        <param name="encoding">Codierung, dient zum Serialisieren von Nachrichten auf Blobs. Unterstützte Werte sind "Avro" und "Avrodeflate". Standardwert ist "Avro".</param>
        <summary>
            Initialisiert eine neue Instanz der RoutingStorageContainerProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BatchFrequencyInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; BatchFrequencyInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; BatchFrequencyInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.BatchFrequencyInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property BatchFrequencyInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.BatchFrequencyInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.BatchFrequencyInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="batchFrequencyInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest Zeitintervall, die mit der Blobs in den Speicher geschrieben werden.
            Wert muss zwischen 60 und 720 Sekunden liegen. Standardwert ist 300 Sekunden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionString">
      <MemberSignature Language="C#" Value="public string ConnectionString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ConnectionString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.ConnectionString" />
      <MemberSignature Language="VB.NET" Value="Public Property ConnectionString As String" />
      <MemberSignature Language="F#" Value="member this.ConnectionString : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.ConnectionString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="connectionString")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Verbindungszeichenfolge des Speicherkontos.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerName">
      <MemberSignature Language="C#" Value="public string ContainerName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.ContainerName" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerName As String" />
      <MemberSignature Language="F#" Value="member this.ContainerName : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.ContainerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen des Speichercontainers im Speicherkonto.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encoding">
      <MemberSignature Language="C#" Value="public string Encoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Encoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.Encoding" />
      <MemberSignature Language="VB.NET" Value="Public Property Encoding As String" />
      <MemberSignature Language="F#" Value="member this.Encoding : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.Encoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encoding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt sie fest, Codierung, die zum Serialisieren von Nachrichten in Blobs verwendet wird.
            Unterstützte Werte sind "Avro" und "Avrodeflate". Standardwert ist "Avro".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileNameFormat">
      <MemberSignature Language="C#" Value="public string FileNameFormat { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FileNameFormat" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.FileNameFormat" />
      <MemberSignature Language="VB.NET" Value="Public Property FileNameFormat As String" />
      <MemberSignature Language="F#" Value="member this.FileNameFormat : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.FileNameFormat" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileNameFormat")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab, oder legt ihn fest-Dateiformat für das Blob. Standardformat lautet {Iothub} / {partition} / {JJJJ} / {MM} / {TT} / {"hh"} / {mm}. Alle Parameter müssen angegeben werden, jedoch neu angeordnet werden können.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxChunkSizeInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxChunkSizeInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxChunkSizeInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.MaxChunkSizeInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxChunkSizeInBytes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxChunkSizeInBytes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.MaxChunkSizeInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="maxChunkSizeInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die maximale Anzahl von Bytes für jedes Blob in den Speicher geschrieben. Wert muss zwischen 10485760(10MB) und 524288000(500MB) liegen. Standardwert ist 314572800(300MB).
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen, der diesen Endpunkt identifiziert. Der Name kann nur alphanumerische Zeichen, Punkte, Unterstriche, Bindestriche enthalten und besitzt eine maximale Länge von 64 Zeichen lang sein. Die folgenden Namen sind reserviert: Ereignisse, OperationsMonitoringEvents, FileNotifications, $default. Endpunktnamen müssen über Endpunkttypen eindeutig sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceGroup">
      <MemberSignature Language="C#" Value="public string ResourceGroup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceGroup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.ResourceGroup" />
      <MemberSignature Language="VB.NET" Value="Public Property ResourceGroup As String" />
      <MemberSignature Language="F#" Value="member this.ResourceGroup : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.ResourceGroup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="resourceGroup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Namen der Ressourcengruppe des Speicherkontos.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="subscriptionId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Abonnement-ID des Speicherkontos.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.RoutingStorageContainerProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="routingStorageContainerProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>