<Type Name="CaptureDescription" FullName="Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription">
  <TypeSignature Language="C#" Value="public class CaptureDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CaptureDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription" />
  <TypeSignature Language="VB.NET" Value="Public Class CaptureDescription" />
  <TypeSignature Language="F#" Value="type CaptureDescription = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eigenschaften zum Konfigurieren der Capture-Beschreibung für den eventhub
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CaptureDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der CaptureDescription-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CaptureDescription (Nullable&lt;bool&gt; enabled = null, Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt; encoding = null, Nullable&lt;int&gt; intervalInSeconds = null, Nullable&lt;int&gt; sizeLimitInBytes = null, Microsoft.Azure.Management.ServiceBus.Models.Destination destination = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;bool&gt; enabled, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt; encoding, valuetype System.Nullable`1&lt;int32&gt; intervalInSeconds, valuetype System.Nullable`1&lt;int32&gt; sizeLimitInBytes, class Microsoft.Azure.Management.ServiceBus.Models.Destination destination) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.#ctor(System.Nullable{System.Boolean},System.Nullable{Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription},System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.Azure.Management.ServiceBus.Models.Destination)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription : Nullable&lt;bool&gt; * Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt; * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.ServiceBus.Models.Destination -&gt; Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription" Usage="new Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription (enabled, encoding, intervalInSeconds, sizeLimitInBytes, destination)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="enabled" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="encoding" Type="System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt;" />
        <Parameter Name="intervalInSeconds" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="sizeLimitInBytes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="destination" Type="Microsoft.Azure.Management.ServiceBus.Models.Destination" />
      </Parameters>
      <Docs>
        <param name="enabled">Ein Wert, der angibt, ob die Beschreibung des Capture aktiviert ist. </param>
        <param name="encoding">Listet die möglichen Werte für das Codierungsformat von Capture-Beschreibung an. Folgende Werte sind möglich: "Avro", "AvroDeflate"</param>
        <param name="intervalInSeconds">Die Zeitfenster können Sie die Häufigkeit, mit denen die Erfassung des Azure-Blobs ausgeführt, sollte der Wert zwischen 60 und 900 Sekunden, festlegen</param>
        <param name="sizeLimitInBytes">Das Fenster der Größe definiert, die Menge der Daten in Ihren Event Hub vor einem Vorgang Capture aufgebaut, Wert muss zwischen 10485760 und 524288000 bytes</param>
        <param name="destination">Eigenschaften des Ziels, wo Capture gespeichert werden sollen. (Speicherkonto, Blob-Namen)</param>
        <summary>
            Initialisiert eine neue Instanz der CaptureDescription-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Destination">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ServiceBus.Models.Destination Destination { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ServiceBus.Models.Destination Destination" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.Destination" />
      <MemberSignature Language="VB.NET" Value="Public Property Destination As Destination" />
      <MemberSignature Language="F#" Value="member this.Destination : Microsoft.Azure.Management.ServiceBus.Models.Destination with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.Destination" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="destination")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ServiceBus.Models.Destination</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Eigenschaften des Ziels, wo Capture gespeichert werden sollen. (Speicherkonto, Blob-Namen)
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; Enabled { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public Property Enabled As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.Enabled : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.Enabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Wert, der angibt, ob die Beschreibung des Capture aktiviert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Encoding">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt; Encoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt; Encoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.Encoding" />
      <MemberSignature Language="VB.NET" Value="Public Property Encoding As Nullable(Of EncodingCaptureDescription)" />
      <MemberSignature Language="F#" Value="member this.Encoding : Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.Encoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="encoding")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ServiceBus.Models.EncodingCaptureDescription&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Listet die möglichen Werte für das Codierungsformat von Capture-Beschreibung. Folgende Werte sind möglich: "Avro", "AvroDeflate"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IntervalInSeconds">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; IntervalInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; IntervalInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.IntervalInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property IntervalInSeconds As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.IntervalInSeconds : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.IntervalInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="intervalInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit Fenster ermöglicht es Ihnen, legen Sie die Häufigkeit, mit denen die Erfassung des Azure-Blobs ausgeführt, sollte der Wert zwischen 60 und 900 Sekunden, fest
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SizeLimitInBytes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; SizeLimitInBytes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; SizeLimitInBytes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.SizeLimitInBytes" />
      <MemberSignature Language="VB.NET" Value="Public Property SizeLimitInBytes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.SizeLimitInBytes : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.SizeLimitInBytes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sizeLimitInBytes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Fenstergröße aufgebaut Datenmenge in Ihren Event Hub vor einem Capture-Vorgang definiert, sollte Wert zwischen 10485760 und 524288000 Bytes sein.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Models.CaptureDescription.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="captureDescription.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus</AssemblyName>
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