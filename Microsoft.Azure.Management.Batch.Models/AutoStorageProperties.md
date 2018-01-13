<Type Name="AutoStorageProperties" FullName="Microsoft.Azure.Management.Batch.Models.AutoStorageProperties">
  <TypeSignature Language="C#" Value="public class AutoStorageProperties : Microsoft.Azure.Management.Batch.Models.AutoStorageBaseProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoStorageProperties extends Microsoft.Azure.Management.Batch.Models.AutoStorageBaseProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.AutoStorageProperties" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoStorageProperties&#xA;Inherits AutoStorageBaseProperties" />
  <TypeSignature Language="F#" Value="type AutoStorageProperties = class&#xA;    inherit AutoStorageBaseProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Batch.Models.AutoStorageBaseProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Enthält Informationen über das automatische Speicherkonto ein Batch-Konto zugeordnet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoStorageProperties ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoStorageProperties.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der AutoStorageProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoStorageProperties (string storageAccountId, DateTime lastKeySync);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string storageAccountId, valuetype System.DateTime lastKeySync) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoStorageProperties.#ctor(System.String,System.DateTime)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (storageAccountId As String, lastKeySync As DateTime)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.AutoStorageProperties : string * DateTime -&gt; Microsoft.Azure.Management.Batch.Models.AutoStorageProperties" Usage="new Microsoft.Azure.Management.Batch.Models.AutoStorageProperties (storageAccountId, lastKeySync)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageAccountId" Type="System.String" />
        <Parameter Name="lastKeySync" Type="System.DateTime" />
      </Parameters>
      <Docs>
        <param name="storageAccountId">Die Ressourcen-ID des Speicherkontos für den Auto-Speicherkonto verwendet werden soll.</param>
        <param name="lastKeySync">Die UTC-Zeit, zu dem Schlüssel zuletzt mit dem Batch-Konto synchronisiert wurden.</param>
        <summary>
            Initialisiert eine neue Instanz der AutoStorageProperties-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastKeySync">
      <MemberSignature Language="C#" Value="public DateTime LastKeySync { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastKeySync" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.AutoStorageProperties.LastKeySync" />
      <MemberSignature Language="VB.NET" Value="Public Property LastKeySync As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastKeySync : DateTime with get, set" Usage="Microsoft.Azure.Management.Batch.Models.AutoStorageProperties.LastKeySync" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lastKeySync")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die UTC-Zeit, zu der zuletzt Speicherschlüssel mit dem Batch-Konto synchronisiert wurden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public override void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.AutoStorageProperties.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Validate ()" />
      <MemberSignature Language="F#" Value="override this.Validate : unit -&gt; unit" Usage="autoStorageProperties.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
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