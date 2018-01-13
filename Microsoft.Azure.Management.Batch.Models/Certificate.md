<Type Name="Certificate" FullName="Microsoft.Azure.Management.Batch.Models.Certificate">
  <TypeSignature Language="C#" Value="public class Certificate : Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Certificate extends Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.Certificate" />
  <TypeSignature Language="VB.NET" Value="Public Class Certificate&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type Certificate = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Batch.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Enthält Informationen über ein Zertifikat an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Certificate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Certificate.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Certificate (string id = null, string name = null, string type = null, string etag = null, string thumbprintAlgorithm = null, string thumbprint = null, Microsoft.Azure.Management.Batch.Models.CertificateFormat format = Microsoft.Azure.Management.Batch.Models.CertificateFormat.Pfx, Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState provisioningState = Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState.Succeeded, Nullable&lt;DateTime&gt; provisioningStateTransitionTime = null, Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState previousProvisioningState = Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState.Succeeded, Nullable&lt;DateTime&gt; previousProvisioningStateTransitionTime = null, string publicData = null, Microsoft.Azure.Management.Batch.Models.DeleteCertificateError deleteCertificateError = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string etag, string thumbprintAlgorithm, string thumbprint, valuetype Microsoft.Azure.Management.Batch.Models.CertificateFormat format, valuetype Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; provisioningStateTransitionTime, valuetype Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState previousProvisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; previousProvisioningStateTransitionTime, string publicData, class Microsoft.Azure.Management.Batch.Models.DeleteCertificateError deleteCertificateError) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Certificate.#ctor(System.String,System.String,System.String,System.String,System.String,System.String,Microsoft.Azure.Management.Batch.Models.CertificateFormat,Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState,System.Nullable{System.DateTime},Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState,System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.Batch.Models.DeleteCertificateError)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.Certificate : string * string * string * string * string * string * Microsoft.Azure.Management.Batch.Models.CertificateFormat * Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.Batch.Models.DeleteCertificateError -&gt; Microsoft.Azure.Management.Batch.Models.Certificate" Usage="new Microsoft.Azure.Management.Batch.Models.Certificate (id, name, type, etag, thumbprintAlgorithm, thumbprint, format, provisioningState, provisioningStateTransitionTime, previousProvisioningState, previousProvisioningStateTransitionTime, publicData, deleteCertificateError)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="thumbprintAlgorithm" Type="System.String" />
        <Parameter Name="thumbprint" Type="System.String" />
        <Parameter Name="format" Type="Microsoft.Azure.Management.Batch.Models.CertificateFormat" />
        <Parameter Name="provisioningState" Type="Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState" />
        <Parameter Name="provisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="previousProvisioningState" Type="Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState" />
        <Parameter Name="previousProvisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="publicData" Type="System.String" />
        <Parameter Name="deleteCertificateError" Type="Microsoft.Azure.Management.Batch.Models.DeleteCertificateError" />
      </Parameters>
      <Docs>
        <param name="id">Die ID der Ressource.</param>
        <param name="name">Der Name der Ressource.</param>
        <param name="type">Der Typ der Ressource.</param>
        <param name="etag">Das ETag der Ressource, für Parallelität-Anweisungen verwendet werden soll.</param>
        <param name="thumbprintAlgorithm">Der Algorithmus den Fingerabdruck des Zertifikats</param>
        <param name="thumbprint">Der Fingerabdruck des Zertifikats</param>
        <param name="format">Das Format des Zertifikat - Pfx oder Cer. Wenn nicht angegeben, ist die Standardeinstellung Pfx. Folgende Werte sind möglich: "Pfx", ". Cer"</param>
        <param name="provisioningState">Der Bereitstellungsstatus der Ressource</param>
        <param name="provisioningStateTransitionTime">Der Zeitpunkt, an dem das Zertifikat in seinem aktuellen Zustand übergegangen.</param>
        <param name="previousProvisioningState">Der vorherige bereitgestellte Status der Ressource. Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Löschen", "fehlgeschlagen"</param>
        <param name="previousProvisioningStateTransitionTime">Der Zeitpunkt, an dem das Zertifikat in den vorherigen Zustand übergegangen.</param>
        <param name="publicData">Der öffentliche Schlüssel des Zertifikats.</param>
        <param name="deleteCertificateError">Der Fehler beim Löschen des Zertifikats trat</param>
        <summary>
            Initialisiert eine neue Instanz der Zertifikat-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteCertificateError">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.DeleteCertificateError DeleteCertificateError { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.DeleteCertificateError DeleteCertificateError" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.DeleteCertificateError" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeleteCertificateError As DeleteCertificateError" />
      <MemberSignature Language="F#" Value="member this.DeleteCertificateError : Microsoft.Azure.Management.Batch.Models.DeleteCertificateError" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.DeleteCertificateError" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deleteCertificateError")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.DeleteCertificateError</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Fehler beim Löschen des Zertifikats eingetreten ab
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies wird nur zurückgegeben, wenn das Zertifikat ProvisioningState "fehlgeschlagen".
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Format">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CertificateFormat Format { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.CertificateFormat Format" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.Format" />
      <MemberSignature Language="VB.NET" Value="Public Property Format As CertificateFormat" />
      <MemberSignature Language="F#" Value="member this.Format : Microsoft.Azure.Management.Batch.Models.CertificateFormat with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.Format" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.format")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateFormat</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Format des Zertifikat - Pfx oder Cer. Wenn nicht angegeben, ist die Standardeinstellung Pfx. Folgende Werte sind möglich: "Pfx", ". Cer"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState PreviousProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState PreviousProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.PreviousProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousProvisioningState As CertificateProvisioningState" />
      <MemberSignature Language="F#" Value="member this.PreviousProvisioningState : Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.PreviousProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.previousProvisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den vorherigen bereitgestellten Zustand der Ressource ab. Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Löschen", "fehlgeschlagen"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PreviousProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; PreviousProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; PreviousProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.PreviousProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PreviousProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.PreviousProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.PreviousProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.previousProvisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt, an dem das Zertifikat in den vorherigen Zustand übergegangen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As CertificateProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.CertificateProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             Ruft den Bereitstellungsstatus der Ressource
             </summary>
        <value>To be added.</value>
        <remarks>
             Gültige Werte:
            
             Erfolgreich – ist das Zertifikat für die Verwendung in Pools verfügbar.
             Wird gelöscht – der Benutzer fordert, dass das Zertifikat gelöscht werden, aber der Delete-Vorgang wurde noch nicht abgeschlossen. Sie können nicht auf das Zertifikat beim Erstellen oder Aktualisieren von Pools verweisen.
             Fehler - der Benutzer angefordert, dass das Zertifikat gelöscht werden, aber hinzu, die Verweise auf das Zertifikat immer noch vorhanden sind, oder noch auf einem oder mehreren Computeknoten installiert ist. (Letzteres kann auftreten, wenn das Zertifikat aus dem Pool entfernt wurde, aber der Knoten noch nicht neu gestartet. Knoten aktualisieren ihre Zertifikate nur beim Neustart.) Sie können den Vorgang "Abbrechen" Zertifikat löschen, um den Löschvorgang abzubrechen, oder der Löschvorgang des Zertifikats den Löschvorgang wiederholt. Folgende Werte sind möglich: "Erfolgreich abgeschlossen", "Löschen", "fehlgeschlagen"
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.ProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.ProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Zeitpunkt, an dem das Zertifikat in seinem aktuellen Zustand übergegangen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicData">
      <MemberSignature Language="C#" Value="public string PublicData { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicData" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.PublicData" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicData As String" />
      <MemberSignature Language="F#" Value="member this.PublicData : string" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.PublicData" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.publicData")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den öffentlichen Schlüssel des Zertifikats ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.Thumbprint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Fingerabdruck des Zertifikats
            </summary>
        <value>To be added.</value>
        <remarks>
            Dieser muss den Fingerabdruck aus dem Namen entsprechen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ThumbprintAlgorithm">
      <MemberSignature Language="C#" Value="public string ThumbprintAlgorithm { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ThumbprintAlgorithm" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Certificate.ThumbprintAlgorithm" />
      <MemberSignature Language="VB.NET" Value="Public Property ThumbprintAlgorithm As String" />
      <MemberSignature Language="F#" Value="member this.ThumbprintAlgorithm : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Certificate.ThumbprintAlgorithm" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.thumbprintAlgorithm")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Hashalgorithmus den Fingerabdruck des Zertifikats
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies muss den ersten Teil der Name des Zertifikats übereinstimmen.
            Derzeit muss "SHA1" sein.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Certificate.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="certificate.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
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