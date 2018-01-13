<Type Name="ExitCodeMapping" FullName="Microsoft.Azure.Batch.ExitCodeMapping">
  <TypeSignature Language="C#" Value="public class ExitCodeMapping" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitCodeMapping extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ExitCodeMapping" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitCodeMapping" />
  <TypeSignature Language="F#" Value="type ExitCodeMapping = class&#xA;    interface ITransportObjectProvider&lt;ExitCodeMapping&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="3e668-101">Ein Exitcode des Prozesses und wie der Batch-Dienst reagieren soll, wenn eine Aufgabe beendet, mit dem wird Exitcode.</span><span class="sxs-lookup"><span data-stu-id="3e668-101">A process exit code and how the Batch service should respond if a task exits with that exit code.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitCodeMapping (int code, Microsoft.Azure.Batch.ExitOptions exitOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 code, class Microsoft.Azure.Batch.ExitOptions exitOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ExitCodeMapping.#ctor(System.Int32,Microsoft.Azure.Batch.ExitOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ExitCodeMapping : int * Microsoft.Azure.Batch.ExitOptions -&gt; Microsoft.Azure.Batch.ExitCodeMapping" Usage="new Microsoft.Azure.Batch.ExitCodeMapping (code, exitOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="code" Type="System.Int32" />
        <Parameter Name="exitOptions" Type="Microsoft.Azure.Batch.ExitOptions" />
      </Parameters>
      <Docs>
        <param name="code"><span data-ttu-id="3e668-102">Der Exitcode des Prozesses.</span><span class="sxs-lookup"><span data-stu-id="3e668-102">The process exit code.</span></span></param>
        <param name="exitOptions"><span data-ttu-id="3e668-103">Wie der Batch-Dienst reagieren soll, wenn die Aufgabe dieser Exitcode beendet wird.</span><span class="sxs-lookup"><span data-stu-id="3e668-103">How the Batch service should respond if the task exits with this exit code.</span></span></param>
        <summary>
            <span data-ttu-id="3e668-104">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.ExitCodeMapping" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="3e668-104">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.ExitCodeMapping" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Code">
      <MemberSignature Language="C#" Value="public int Code { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Code" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitCodeMapping.Code" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Code As Integer" />
      <MemberSignature Language="F#" Value="member this.Code : int" Usage="Microsoft.Azure.Batch.ExitCodeMapping.Code" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e668-105">Ruft den Exitcode des Prozesses ab.</span><span class="sxs-lookup"><span data-stu-id="3e668-105">Gets the process exit code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ExitOptions ExitOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ExitOptions ExitOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitCodeMapping.ExitOptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExitOptions As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.ExitOptions : Microsoft.Azure.Batch.ExitOptions" Usage="Microsoft.Azure.Batch.ExitCodeMapping.ExitOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ExitOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3e668-106">Ruft ab, wie der Batch-Dienst reagieren soll, wenn die Aufgabe dieser Exitcode beendet wird.</span><span class="sxs-lookup"><span data-stu-id="3e668-106">Gets how the Batch service should respond if the task exits with this exit code.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>