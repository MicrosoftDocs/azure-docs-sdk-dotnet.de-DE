<Type Name="MultiInstanceSettings" FullName="Microsoft.Azure.Batch.MultiInstanceSettings">
  <TypeSignature Language="C#" Value="public class MultiInstanceSettings" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MultiInstanceSettings extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.MultiInstanceSettings" />
  <TypeSignature Language="VB.NET" Value="Public Class MultiInstanceSettings" />
  <TypeSignature Language="F#" Value="type MultiInstanceSettings = class&#xA;    interface ITransportObjectProvider&lt;MultiInstanceSettings&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="13d83-101">Einstellungen auf, die angeben, wie eine Aufgabe mit mehreren Instanzen ausgeführt werden soll.</span><span class="sxs-lookup"><span data-stu-id="13d83-101">Settings which specify how to run a multi-instance task.</span></span> <span data-ttu-id="13d83-102">Mit mehreren Instanzen Tasks werden häufig verwendet, um MPI-Aufgaben zu unterstützen.</span><span class="sxs-lookup"><span data-stu-id="13d83-102">Multi-instance tasks are commonly used to support MPI tasks.</span></span> <span data-ttu-id="13d83-103">Weitere Informationen finden Sie unter https://azure.microsoft.com/documentation/articles/batch-mpi/.</span><span class="sxs-lookup"><span data-stu-id="13d83-103">For more information see https://azure.microsoft.com/documentation/articles/batch-mpi/.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MultiInstanceSettings (string coordinationCommandLine, Nullable&lt;int&gt; numberOfInstances = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string coordinationCommandLine, valuetype System.Nullable`1&lt;int32&gt; numberOfInstances) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.MultiInstanceSettings.#ctor(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (coordinationCommandLine As String, Optional numberOfInstances As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.MultiInstanceSettings : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Batch.MultiInstanceSettings" Usage="new Microsoft.Azure.Batch.MultiInstanceSettings (coordinationCommandLine, numberOfInstances)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="coordinationCommandLine" Type="System.String" />
        <Parameter Name="numberOfInstances" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="coordinationCommandLine"><span data-ttu-id="13d83-104">Der Befehl, auf die Knoten für die Koordination zwischen der Unteraufgaben Instanzen ausgeführt werden.</span><span class="sxs-lookup"><span data-stu-id="13d83-104">The command to run on the compute node instances for coordinating among the subtasks.</span></span></param>
        <param name="numberOfInstances"><span data-ttu-id="13d83-105">Die Anzahl der Compute-Knoten, die von der Aufgabe mit mehreren Instanzen erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="13d83-105">The number of compute nodes required by the multi-instance task.</span></span></param>
        <summary>
            <span data-ttu-id="13d83-106">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.MultiInstanceSettings" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="13d83-106">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.MultiInstanceSettings" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CommonResourceFiles">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt; CommonResourceFiles { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.ResourceFile&gt; CommonResourceFiles" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.MultiInstanceSettings.CommonResourceFiles" />
      <MemberSignature Language="VB.NET" Value="Public Property CommonResourceFiles As IList(Of ResourceFile)" />
      <MemberSignature Language="F#" Value="member this.CommonResourceFiles : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt; with get, set" Usage="Microsoft.Azure.Batch.MultiInstanceSettings.CommonResourceFiles" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.ResourceFile&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13d83-107">Ruft ab oder Festlegen einer Liste von Dateien, die der Batch-Dienst vor dem Ausführen der Befehlszeile Koordinierung heruntergeladen wird.</span><span class="sxs-lookup"><span data-stu-id="13d83-107">Gets or sets a list of files that the Batch service will download before running the coordination command line.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="13d83-108">Der Unterschied zwischen allgemeinen Ressourcendateien und Ressourcendateien Aufgabe ist, dass allgemeine Ressourcendateien für alle Unteraufgaben an, einschließlich der primären heruntergeladen werden, während nur für die primäre Aufgabe Ressourcendateien heruntergeladen werden.</span><span class="sxs-lookup"><span data-stu-id="13d83-108">The difference between common resource files and task resource files is that common resource files are downloaded for all subtasks including the primary, whereas task resource files are downloaded only for the primary.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CoordinationCommandLine">
      <MemberSignature Language="C#" Value="public string CoordinationCommandLine { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CoordinationCommandLine" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberSignature Language="VB.NET" Value="Public Property CoordinationCommandLine As String" />
      <MemberSignature Language="F#" Value="member this.CoordinationCommandLine : string with get, set" Usage="Microsoft.Azure.Batch.MultiInstanceSettings.CoordinationCommandLine" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13d83-109">Abrufen oder Festlegen des Befehls zum Ausführen auf Instanzen der Knoten für die Koordination zwischen die Unteraufgaben an.</span><span class="sxs-lookup"><span data-stu-id="13d83-109">Gets or sets the command to run on the compute node instances for coordinating among the subtasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfInstances">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; NumberOfInstances { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; NumberOfInstances" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.MultiInstanceSettings.NumberOfInstances" />
      <MemberSignature Language="VB.NET" Value="Public Property NumberOfInstances As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.NumberOfInstances : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.MultiInstanceSettings.NumberOfInstances" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="13d83-110">Ruft ab oder legt die Anzahl von Serverknoten, die von der Aufgabe mit mehreren Instanzen erforderlich sind.</span><span class="sxs-lookup"><span data-stu-id="13d83-110">Gets or sets the number of compute nodes required by the multi-instance task.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>