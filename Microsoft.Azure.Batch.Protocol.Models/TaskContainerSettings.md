<Type Name="TaskContainerSettings" FullName="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings">
  <TypeSignature Language="C#" Value="public class TaskContainerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskContainerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskContainerSettings" />
  <TypeSignature Language="F#" Value="type TaskContainerSettings = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Die Container-Einstellungen für eine Aufgabe.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskContainerSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der TaskContainerSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskContainerSettings (string imageName, string containerRunOptions = null, Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry registry = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string imageName, string containerRunOptions, class Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry registry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.#ctor(System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (imageName As String, Optional containerRunOptions As String = null, Optional registry As ContainerRegistry = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings : string * string * Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry -&gt; Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings" Usage="new Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings (imageName, containerRunOptions, registry)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="containerRunOptions" Type="System.String" />
        <Parameter Name="registry" Type="Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry" />
      </Parameters>
      <Docs>
        <param name="imageName">Das Bild, verwenden Sie zum Erstellen des Containers, in dem der Task ausgeführt wird.</param>
        <param name="containerRunOptions">Zusätzliche Optionen für den Container erstellen Befehl.</param>
        <param name="registry">Der privaten Registrierung, die containerimage enthält.</param>
        <summary>
            Initialisiert eine neue Instanz der TaskContainerSettings-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRunOptions">
      <MemberSignature Language="C#" Value="public string ContainerRunOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerRunOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.ContainerRunOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property ContainerRunOptions As String" />
      <MemberSignature Language="F#" Value="member this.ContainerRunOptions : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.ContainerRunOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="containerRunOptions")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt fest, die zusätzliche Optionen für den Container zu erstellen-Befehl.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dieser zusätzlichen Optionen werden als Argumente an den Befehl "Docker erstellen", zusätzlich zu den gesteuert, die vom Batch-Dienst bereitgestellt.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageName">
      <MemberSignature Language="C#" Value="public string ImageName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ImageName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.ImageName" />
      <MemberSignature Language="VB.NET" Value="Public Property ImageName As String" />
      <MemberSignature Language="F#" Value="member this.ImageName : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.ImageName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="imageName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Bild zu verwenden, um den Container zu erstellen, in dem der Task ausgeführt wird.
            </summary>
        <value>To be added.</value>
        <remarks>
            Dies ist die vollständige bildverweises wie "Docker Pull" angegeben werden, würden. Wenn kein Tag, als Teil der Name, der das Tag angegeben ist ": neueste" wird als Standardwert verwendet.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Registry">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry Registry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry Registry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.Registry" />
      <MemberSignature Language="VB.NET" Value="Public Property Registry As ContainerRegistry" />
      <MemberSignature Language="F#" Value="member this.Registry : Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.Registry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="registry")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ContainerRegistry</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder festlegen die private Registrierung, die containerimage enthält.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Einstellung kann ausgelassen werden, wenn bei der Erstellung der Pool bereits bereitgestellt wurde.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.TaskContainerSettings.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="taskContainerSettings.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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