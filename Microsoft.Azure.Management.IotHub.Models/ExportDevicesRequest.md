<Type Name="ExportDevicesRequest" FullName="Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest">
  <TypeSignature Language="C#" Value="public class ExportDevicesRequest" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExportDevicesRequest extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest" />
  <TypeSignature Language="VB.NET" Value="Public Class ExportDevicesRequest" />
  <TypeSignature Language="F#" Value="type ExportDevicesRequest = class" />
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
            Verwenden Sie, um Parameter bereitzustellen, wenn Sie einen Export alle Geräte in den IoT Hub anfordern.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportDevicesRequest ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der ExportDevicesRequest-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExportDevicesRequest (string exportBlobContainerUri, bool excludeKeys);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string exportBlobContainerUri, bool excludeKeys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest.#ctor(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (exportBlobContainerUri As String, excludeKeys As Boolean)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest : string * bool -&gt; Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest" Usage="new Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest (exportBlobContainerUri, excludeKeys)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exportBlobContainerUri" Type="System.String" />
        <Parameter Name="excludeKeys" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="exportBlobContainerUri">Der Export-Blob-Container URI.</param>
        <param name="excludeKeys">Der Wert, der angibt, ob Schlüssel während des Exports ausgeschlossen werden sollen.</param>
        <summary>
            Initialisiert eine neue Instanz der ExportDevicesRequest-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExcludeKeys">
      <MemberSignature Language="C#" Value="public bool ExcludeKeys { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExcludeKeys" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest.ExcludeKeys" />
      <MemberSignature Language="VB.NET" Value="Public Property ExcludeKeys As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExcludeKeys : bool with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest.ExcludeKeys" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ExcludeKeys")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Wert, der angibt, ob Schlüssel während des Exports ausgeschlossen werden sollen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportBlobContainerUri">
      <MemberSignature Language="C#" Value="public string ExportBlobContainerUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ExportBlobContainerUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest.ExportBlobContainerUri" />
      <MemberSignature Language="VB.NET" Value="Public Property ExportBlobContainerUri As String" />
      <MemberSignature Language="F#" Value="member this.ExportBlobContainerUri : string with get, set" Usage="Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest.ExportBlobContainerUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.IotHub</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="ExportBlobContainerUri")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Exportcontainer für BLOB-URI.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.IotHub.Models.ExportDevicesRequest.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="exportDevicesRequest.Validate " />
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