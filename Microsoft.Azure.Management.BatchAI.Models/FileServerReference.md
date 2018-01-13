<Type Name="FileServerReference" FullName="Microsoft.Azure.Management.BatchAI.Models.FileServerReference">
  <TypeSignature Language="C#" Value="public class FileServerReference" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileServerReference extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.FileServerReference" />
  <TypeSignature Language="VB.NET" Value="Public Class FileServerReference" />
  <TypeSignature Language="F#" Value="type FileServerReference = class" />
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
            Stellt die erforderlichen Informationen, die für den Dienst zum Bereitstellen von Azure-Dateifreigabe auf den Clusterknoten können.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileServerReference ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServerReference.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der FileServerReference-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileServerReference (Microsoft.Azure.Management.BatchAI.Models.ResourceId fileServer, string relativeMountPath, string sourceDirectory = null, string mountOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.BatchAI.Models.ResourceId fileServer, string relativeMountPath, string sourceDirectory, string mountOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServerReference.#ctor(Microsoft.Azure.Management.BatchAI.Models.ResourceId,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (fileServer As ResourceId, relativeMountPath As String, Optional sourceDirectory As String = null, Optional mountOptions As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.FileServerReference : Microsoft.Azure.Management.BatchAI.Models.ResourceId * string * string * string -&gt; Microsoft.Azure.Management.BatchAI.Models.FileServerReference" Usage="new Microsoft.Azure.Management.BatchAI.Models.FileServerReference (fileServer, relativeMountPath, sourceDirectory, mountOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="fileServer" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
        <Parameter Name="relativeMountPath" Type="System.String" />
        <Parameter Name="sourceDirectory" Type="System.String" />
        <Parameter Name="mountOptions" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fileServer">Verweis auf die Server-Ressource "File".</param>
        <param name="relativeMountPath">Gibt den relativen Pfad auf den Computeknoten, von dem der Dateiserver bereitgestellt wird.</param>
        <param name="sourceDirectory">Gibt das Quellverzeichnis Dateiserver, die bereitgestellt werden muss.</param>
        <param name="mountOptions">Gibt die Mount-Optionen für Dateiserver.</param>
        <summary>
            Initialisiert eine neue Instanz der FileServerReference-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FileServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId FileServer { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId FileServer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerReference.FileServer" />
      <MemberSignature Language="VB.NET" Value="Public Property FileServer As ResourceId" />
      <MemberSignature Language="F#" Value="member this.FileServer : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerReference.FileServer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="fileServer")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ResourceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Verweis auf die Server-Ressource "File".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MountOptions">
      <MemberSignature Language="C#" Value="public string MountOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MountOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerReference.MountOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property MountOptions As String" />
      <MemberSignature Language="F#" Value="member this.MountOptions : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerReference.MountOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="mountOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Gibt Optionen für Dateiserver an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RelativeMountPath">
      <MemberSignature Language="C#" Value="public string RelativeMountPath { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RelativeMountPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerReference.RelativeMountPath" />
      <MemberSignature Language="VB.NET" Value="Public Property RelativeMountPath As String" />
      <MemberSignature Language="F#" Value="member this.RelativeMountPath : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerReference.RelativeMountPath" />
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
            Ruft ab oder legt gibt den relativen Pfad auf den Computeknoten, von dem der Dateiserver bereitgestellt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Beachten Sie, dass alle Dateifreigaben unter "Location" $AZ_BATCHAI_MOUNT_ROOT bereitgestellt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceDirectory">
      <MemberSignature Language="C#" Value="public string SourceDirectory { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceDirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServerReference.SourceDirectory" />
      <MemberSignature Language="VB.NET" Value="Public Property SourceDirectory As String" />
      <MemberSignature Language="F#" Value="member this.SourceDirectory : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServerReference.SourceDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sourceDirectory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt gibt das Quellverzeichnis Dateiserver, die bereitgestellt werden muss.
            </summary>
        <value>To be added.</value>
        <remarks>
            Wenn diese Eigenschaft nicht angegeben ist, wird der gesamte Dateiserver bereitgestellt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServerReference.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fileServerReference.Validate " />
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