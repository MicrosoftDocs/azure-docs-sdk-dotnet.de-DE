<Type Name="Certificate" FullName="Microsoft.Azure.Batch.Protocol.Models.Certificate">
  <TypeSignature Language="C#" Value="public class Certificate" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Certificate extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.Certificate" />
  <TypeSignature Language="VB.NET" Value="Public Class Certificate" />
  <TypeSignature Language="F#" Value="type Certificate = class" />
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
            Ein Zertifikat, das auf installiert werden kann, Serverknoten und können verwendet werden, um Vorgänge auf dem Computer zu authentifizieren.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Certificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.Certificate.#ctor" />
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
            Initialisiert eine neue Instanz der Zertifikat-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Certificate (string thumbprint = null, string thumbprintAlgorithm = null, string url = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; state = null, Nullable&lt;DateTime&gt; stateTransitionTime = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; previousState = null, Nullable&lt;DateTime&gt; previousStateTransitionTime = null, string publicData = null, Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError deleteCertificateError = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string thumbprint, string thumbprintAlgorithm, string url, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; state, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; stateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; previousState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; previousStateTransitionTime, string publicData, class Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError deleteCertificateError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.Certificate.#ctor(System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.CertificateState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.CertificateState},System.Nullable{System.DateTime},System.String,Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.Certificate : string * string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError -&gt; Microsoft.Azure.Batch.Protocol.Models.Certificate" Usage="new Microsoft.Azure.Batch.Protocol.Models.Certificate (thumbprint, thumbprintAlgorithm, url, state, stateTransitionTime, previousState, previousStateTransitionTime, publicData, deleteCertificateError)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="state" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt;" />
        <Parameter Name="stateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="previousState" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt;" />
        <Parameter Name="previousStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="publicData" Type="System.String" />
        <Parameter Name="deleteCertificateError" Type="Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError" />
      </Parameters>
      <Docs>
        <param name="thumbprint">Der x. 509-Fingerabdruck des Zertifikats.
            Dies ist eine Sequenz von bis zu 40 hexadezimale Ziffern.</param>
        <param name="thumbprintAlgorithm">Der Algorithmus, der zum Ableiten des Fingerabdrucks verwendet wird.</param>
        <param name="url">Die URL des Zertifikats.</param>
        <param name="state">Der aktuelle Status des Zertifikats.</param>
        <param name="stateTransitionTime">Der Zeitpunkt, an dem das Zertifikat in seinem aktuellen Zustand übergegangen.</param>
        <param name="previousState">Der vorherige Status des Zertifikats.</param>
        <param name="previousStateTransitionTime">Der Zeitpunkt, an dem das Zertifikat in den vorherigen Zustand übergegangen.</param>
        <param name="publicData">Der öffentliche Teil des Zertifikats als Base-64-codierte CER-Datei.</param>
        <param name="deleteCertificateError">So löschen Sie dieses Zertifikat beim letzten Versuch aufgetretenen Fehlers.</param>
        <summary>
            Initialisiert eine neue Instanz der Zertifikat-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError DeleteCertificateError { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError DeleteCertificateError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.DeleteCertificateError" />
      <MemberSignature Language="VB.NET" Value="Public Property DeleteCertificateError As DeleteCertificateError" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificateError : Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.DeleteCertificateError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="deleteCertificateError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.DeleteCertificateError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den aufgetretenen Fehler beim letzten Versuch, dieses Zertifikat zu löschen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird festgelegt, nur dann, wenn das Zertifikat im DeleteFailed Zustand befindet.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; PreviousState { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; PreviousState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.PreviousState" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousState As Nullable(Of CertificateState)" />
      <MemberSignature Language="F#" Value="member this.PreviousState : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.PreviousState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den vorherigen Zustand des Zertifikats.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft ist nicht festgelegt werden, wenn das Zertifikat im seinen anfänglichen aktiven Status befindet. Folgende Werte sind möglich: 'active', 'löschen', 'DeleteFailed'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousStateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.PreviousStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property PreviousStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousStateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.PreviousStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="previousStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit, an der das Zertifikat in den vorherigen Zustand übergegangen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft ist nicht festgelegt werden, wenn das Zertifikat im seinen anfänglichen aktiven Status befindet.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicData">
      <MemberSignature Language="C#" Value="public string PublicData { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.PublicData" />
      <MemberSignature Language="VB.NET" Value="Public Property PublicData As String" />
      <MemberSignature Language="F#" Value="member this.PublicData : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.PublicData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="publicData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den öffentlichen Teil des Zertifikats als Base-64-codierte CER-Datei.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; State { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.State" />
      <MemberSignature Language="VB.NET" Value="Public Property State As Nullable(Of CertificateState)" />
      <MemberSignature Language="F#" Value="member this.State : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="state")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.CertificateState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den aktuellen Status des Zertifikats.
            </summary>
        <value>To be added.</value>
        <remarks>
            Folgende Werte sind möglich: 'active', 'löschen', 'DeleteFailed'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="StateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; StateTransitionTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; StateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.StateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public Property StateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.StateTransitionTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.StateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="stateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Zeit, zu der das Zertifikat seinem aktuellen Status angenommen hat.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den x. 509-Fingerabdruck des Zertifikats. Dies ist eine Sequenz von bis zu 40 hexadezimale Ziffern.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.ThumbprintAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="thumbprintAlgorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Hashalgorithmus, der zum Ableiten des Fingerabdrucks verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.Certificate.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.Certificate.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die URL des Zertifikats fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>