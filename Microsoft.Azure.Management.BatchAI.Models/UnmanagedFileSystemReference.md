<Type Name="UnmanagedFileSystemReference" FullName="Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference">
  <TypeSignature Language="C#" Value="public class UnmanagedFileSystemReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit UnmanagedFileSystemReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference" />
  <TypeSignature Language="VB.NET" Value="Public Class UnmanagedFileSystemReference" />
  <TypeSignature Language="F#" Value="type UnmanagedFileSystemReference = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Details des Dateisystems in der Compute-Clusterknoten einbinden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UnmanagedFileSystemReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der UnmanagedFileSystemReference-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public UnmanagedFileSystemReference (string mountCommand, string relativeMountPath);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string mountCommand, string relativeMountPath) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (mountCommand As String, relativeMountPath As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference : string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference" Usage="new Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference (mountCommand, relativeMountPath)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="mountCommand" Type="System.String" />
        <Parameter Name="relativeMountPath" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="mountCommand">Der Befehl verwendet, um nicht verwaltete Dateisystem bereitgestellt.</param>
        <param name="relativeMountPath">Gibt den relativen Pfad auf dem Compute-Clusterknoten, von dem das Dateisystem bereitgestellt werden.</param>
        <summary>
            Initialisiert eine neue Instanz der UnmanagedFileSystemReference-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MountCommand">
      <MemberSignature Language="C#" Value="public string MountCommand { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MountCommand" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference.MountCommand" />
      <MemberSignature Language="VB.NET" Value="Public Property MountCommand As String" />
      <MemberSignature Language="F#" Value="member this.MountCommand : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference.MountCommand" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mountCommand")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Befehl, der verwendet wird, die nicht verwaltete, im Dateisystem bereitgestellt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelativeMountPath">
      <MemberSignature Language="C#" Value="public string RelativeMountPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelativeMountPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference.RelativeMountPath" />
      <MemberSignature Language="VB.NET" Value="Public Property RelativeMountPath As String" />
      <MemberSignature Language="F#" Value="member this.RelativeMountPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference.RelativeMountPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="relativeMountPath")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt den relativen Pfad auf dem Compute-Clusterknoten, von dem das Dateisystem bereitgestellt werden.
            </summary>
        <value>To be added.</value>
        <remarks>
            Beachten Sie, dass alle Dateifreigaben unter "Location" $AZ_BATCHAI_MOUNT_ROOT bereitgestellt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.UnmanagedFileSystemReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="unmanagedFileSystemReference.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
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