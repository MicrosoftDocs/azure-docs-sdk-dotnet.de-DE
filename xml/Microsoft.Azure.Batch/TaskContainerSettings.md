<Type Name="TaskContainerSettings" FullName="Microsoft.Azure.Batch.TaskContainerSettings">
  <TypeSignature Language="C#" Value="public class TaskContainerSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TaskContainerSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.TaskContainerSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class TaskContainerSettings" />
  <TypeSignature Language="F#" Value="type TaskContainerSettings = class&#xA;    interface ITransportObjectProvider&lt;TaskContainerSettings&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="8a9d1-101">Die Container-Einstellungen für eine Aufgabe.</span><span class="sxs-lookup"><span data-stu-id="8a9d1-101">The container settings for a task.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TaskContainerSettings (string imageName, string containerRunOptions = null, Microsoft.Azure.Batch.ContainerRegistry registry = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string imageName, string containerRunOptions, class Microsoft.Azure.Batch.ContainerRegistry registry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.TaskContainerSettings.#ctor(System.String,System.String,Microsoft.Azure.Batch.ContainerRegistry)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (imageName As String, Optional containerRunOptions As String = null, Optional registry As ContainerRegistry = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.TaskContainerSettings : string * string * Microsoft.Azure.Batch.ContainerRegistry -&gt; Microsoft.Azure.Batch.TaskContainerSettings" Usage="new Microsoft.Azure.Batch.TaskContainerSettings (imageName, containerRunOptions, registry)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="imageName" Type="System.String" />
        <Parameter Name="containerRunOptions" Type="System.String" />
        <Parameter Name="registry" Type="Microsoft.Azure.Batch.ContainerRegistry" />
      </Parameters>
      <Docs>
        <param name="imageName"><span data-ttu-id="8a9d1-102">Das Bild, verwenden Sie zum Erstellen des Containers, in dem der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="8a9d1-102">The image to use to create the container in which the task will run.</span></span></param>
        <param name="containerRunOptions"><span data-ttu-id="8a9d1-103">Zusätzliche Optionen für den Container erstellen Befehl.</span><span class="sxs-lookup"><span data-stu-id="8a9d1-103">Additional options to the container create command.</span></span></param>
        <param name="registry"><span data-ttu-id="8a9d1-104">Der privaten Registrierung, die containerimage enthält.</span><span class="sxs-lookup"><span data-stu-id="8a9d1-104">The private registry which contains the container image.</span></span></param>
        <summary>
            <span data-ttu-id="8a9d1-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.TaskContainerSettings" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="8a9d1-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.TaskContainerSettings" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerRunOptions">
      <MemberSignature Language="C#" Value="public string ContainerRunOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContainerRunOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskContainerSettings.ContainerRunOptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerRunOptions As String" />
      <MemberSignature Language="F#" Value="member this.ContainerRunOptions : string" Usage="Microsoft.Azure.Batch.TaskContainerSettings.ContainerRunOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a9d1-106">Ruft zusätzliche Optionen für den Container erstellen Befehl.</span><span class="sxs-lookup"><span data-stu-id="8a9d1-106">Gets additional options to the container create command.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="8a9d1-107">Dieser zusätzlichen Optionen werden als Argumente an den Befehl "Docker erstellen", zusätzlich zu den gesteuert, die vom Batch-Dienst bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="8a9d1-107">These additional options are supplied as arguments to the "docker create" command, in addition to those controlled by the Batch Service.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ImageName">
      <MemberSignature Language="C#" Value="public string ImageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ImageName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskContainerSettings.ImageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ImageName As String" />
      <MemberSignature Language="F#" Value="member this.ImageName : string" Usage="Microsoft.Azure.Batch.TaskContainerSettings.ImageName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a9d1-108">Ruft das Bild zu verwenden, um den Container zu erstellen, in dem der Task ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="8a9d1-108">Gets the image to use to create the container in which the task will run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="8a9d1-109">Dies ist die vollständige bildverweises wie "Docker Pull" angegeben werden, würden.</span><span class="sxs-lookup"><span data-stu-id="8a9d1-109">This is the full image reference, as would be specified to "docker pull".</span></span> <span data-ttu-id="8a9d1-110">Wenn kein Tag, als Teil der Name, der das Tag angegeben ist ": neueste" wird als Standardwert verwendet.</span><span class="sxs-lookup"><span data-stu-id="8a9d1-110">If no tag is provided as part of the image name, the tag ":latest" is used as a default.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Registry">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ContainerRegistry Registry { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ContainerRegistry Registry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.TaskContainerSettings.Registry" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Registry As ContainerRegistry" />
      <MemberSignature Language="F#" Value="member this.Registry : Microsoft.Azure.Batch.ContainerRegistry" Usage="Microsoft.Azure.Batch.TaskContainerSettings.Registry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ContainerRegistry</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8a9d1-111">Ruft den private Registrierung, die containerimage enthält.</span><span class="sxs-lookup"><span data-stu-id="8a9d1-111">Gets the private registry which contains the container image.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="8a9d1-112">Diese Einstellung kann ausgelassen werden, wenn bei der Erstellung der Pool bereits bereitgestellt wurde.</span><span class="sxs-lookup"><span data-stu-id="8a9d1-112">This setting can be omitted if was already provided at pool creation.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>