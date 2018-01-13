<Type Name="StorageAccountCredential" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential">
  <TypeSignature Language="C#" Value="public class StorageAccountCredential : Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StorageAccountCredential extends Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class StorageAccountCredential&#xA;Inherits BaseModel" />
  <TypeSignature Language="F#" Value="type StorageAccountCredential = class&#xA;    inherit BaseModel" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.StorSimple8000Series.Models.BaseModel</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Der Speicherkonto-Anmeldeinformationen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der StorageAccountCredential-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StorageAccountCredential (string endPoint, Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus sslStatus, string id = null, string name = null, string type = null, Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind = null, Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret accessKey = null, Nullable&lt;int&gt; volumesCount = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string endPoint, valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus sslStatus, string id, string name, string type, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; kind, class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret accessKey, valuetype System.Nullable`1&lt;int32&gt; volumesCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.#ctor(System.String,Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Management.StorSimple8000Series.Models.Kind},Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret,System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential : string * Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus * string * string * string * Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt; * Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential (endPoint, sslStatus, id, name, type, kind, accessKey, volumesCount)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="endPoint" Type="System.String" />
        <Parameter Name="sslStatus" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus" />
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="kind" Type="System.Nullable&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.Kind&gt;" />
        <Parameter Name="accessKey" Type="Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret" />
        <Parameter Name="volumesCount" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="endPoint">Der speicherendpunkt</param>
        <param name="sslStatus">Gibt an, ob SSL aktiviert oder deaktiviert werden muss. Folgende Werte sind möglich: "Enabled", "Disabled"</param>
        <param name="id">Die Pfad-ID, die das Objekt eindeutig identifiziert.</param>
        <param name="name">Der Name des Objekts.</param>
        <param name="type">Der hierarchische Typ des Objekts.</param>
        <param name="kind">Die Art des Objekts. Derzeit wird nur Series8000 wird unterstützt. Folgende Werte sind möglich: "Series8000"</param>
        <param name="accessKey">Die Details der das Kennwort für das Speicherkonto.</param>
        <param name="volumesCount">Die Anzahl der Volumes, verwenden die Anmeldeinformationen dieses Speicherkontos.</param>
        <summary>
            Initialisiert eine neue Instanz der StorageAccountCredential-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AccessKey">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret AccessKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret AccessKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.AccessKey" />
      <MemberSignature Language="VB.NET" Value="Public Property AccessKey As AsymmetricEncryptedSecret" />
      <MemberSignature Language="F#" Value="member this.AccessKey : Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.AccessKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.accessKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.AsymmetricEncryptedSecret</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert die Details der das Kennwort für das Speicherkonto.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndPoint">
      <MemberSignature Language="C#" Value="public string EndPoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndPoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.EndPoint" />
      <MemberSignature Language="VB.NET" Value="Public Property EndPoint As String" />
      <MemberSignature Language="F#" Value="member this.EndPoint : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.EndPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.endPoint")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Speicherkonto-Endpunkt
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SslStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus SslStatus { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus SslStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.SslStatus" />
      <MemberSignature Language="VB.NET" Value="Public Property SslStatus As SslStatus" />
      <MemberSignature Language="F#" Value="member this.SslStatus : Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.SslStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sslStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.StorSimple8000Series.Models.SslStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Gibt an, ob SSL aktiviert oder deaktiviert werden muss, ruft ab oder legt ihn fest.
            Folgende Werte sind möglich: "Enabled", "Disabled"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="storageAccountCredential.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
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
    <Member MemberName="VolumesCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; VolumesCount { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; VolumesCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.VolumesCount" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumesCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.VolumesCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.StorageAccountCredential.VolumesCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.volumesCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Volumes, verwenden die Anmeldeinformationen dieses Speicherkontos ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>