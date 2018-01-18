<Type Name="ExitCodeRangeMapping" FullName="Microsoft.Azure.Batch.ExitCodeRangeMapping">
  <TypeSignature Language="C#" Value="public class ExitCodeRangeMapping" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ExitCodeRangeMapping extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" />
  <TypeSignature Language="VB.NET" Value="Public Class ExitCodeRangeMapping" />
  <TypeSignature Language="F#" Value="type ExitCodeRangeMapping = class&#xA;    interface ITransportObjectProvider&lt;ExitCodeRangeMapping&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="17be0-101">Eine Reihe von Exitcodes und wie der Batch-Dienst reagieren soll, wenn eine Aufgabe mit dem Exitcode innerhalb dieses Bereichs beendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="17be0-101">A range of exit codes and how the Batch service should respond if a task exits with an exit code within that range.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ExitCodeRangeMapping (int start, int end, Microsoft.Azure.Batch.ExitOptions exitOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int32 start, int32 end, class Microsoft.Azure.Batch.ExitOptions exitOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.ExitCodeRangeMapping.#ctor(System.Int32,System.Int32,Microsoft.Azure.Batch.ExitOptions)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.ExitCodeRangeMapping : int * int * Microsoft.Azure.Batch.ExitOptions -&gt; Microsoft.Azure.Batch.ExitCodeRangeMapping" Usage="new Microsoft.Azure.Batch.ExitCodeRangeMapping (start, end, exitOptions)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="start" Type="System.Int32" />
        <Parameter Name="end" Type="System.Int32" />
        <Parameter Name="exitOptions" Type="Microsoft.Azure.Batch.ExitOptions" />
      </Parameters>
      <Docs>
        <param name="start"><span data-ttu-id="17be0-102">Die erste Exitcode im Bereich.</span><span class="sxs-lookup"><span data-stu-id="17be0-102">The first exit code in the range.</span></span></param>
        <param name="end"><span data-ttu-id="17be0-103">Der letzte Exitcode im Bereich.</span><span class="sxs-lookup"><span data-stu-id="17be0-103">The last exit code in the range.</span></span></param>
        <param name="exitOptions"><span data-ttu-id="17be0-104">Ein <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.ExitOptions" /> angeben, wie der Batch-Dienst reagieren soll, wenn die Aufgabe beendet, mit dem Exitcode im Bereich wird <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.Start" /> auf <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.End" /> inklusive.</span><span class="sxs-lookup"><span data-stu-id="17be0-104">An <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.ExitOptions" /> specifying how the Batch service should respond if the task exits with an exit code in the range <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.Start" /> to <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.End" /> inclusive.</span></span></param>
        <summary>
            <span data-ttu-id="17be0-105">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="17be0-105">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="End">
      <MemberSignature Language="C#" Value="public int End { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 End" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.End" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property End As Integer" />
      <MemberSignature Language="F#" Value="member this.End : int" Usage="Microsoft.Azure.Batch.ExitCodeRangeMapping.End" />
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
            <span data-ttu-id="17be0-106">Ruft die letzte Exitcode im Bereich ab.</span><span class="sxs-lookup"><span data-stu-id="17be0-106">Gets the last exit code in the range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="17be0-107">Bereiche sind inklusiv.</span><span class="sxs-lookup"><span data-stu-id="17be0-107">Ranges are inclusive.</span></span> <span data-ttu-id="17be0-108">Z. B. wenn ein <see cref="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" /> gibt 8 "und" End 10 starten wird es Exitcodes, 8, 9 und 10 entspricht.</span><span class="sxs-lookup"><span data-stu-id="17be0-108">For example, if an <see cref="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" /> specifies Start 8 and End 10, then it matches exit codes 8, 9 and 10.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExitOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ExitOptions ExitOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ExitOptions ExitOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.ExitOptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExitOptions As ExitOptions" />
      <MemberSignature Language="F#" Value="member this.ExitOptions : Microsoft.Azure.Batch.ExitOptions" Usage="Microsoft.Azure.Batch.ExitCodeRangeMapping.ExitOptions" />
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
            <span data-ttu-id="17be0-109">Ruft eine <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.ExitOptions" /> angeben, wie der Batch-Dienst reagieren soll, wenn die Aufgabe beendet, mit dem Exitcode im Bereich wird <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.Start" /> auf <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.End" /> inklusive.</span><span class="sxs-lookup"><span data-stu-id="17be0-109">Gets an <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.ExitOptions" /> specifying how the Batch service should respond if the task exits with an exit code in the range <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.Start" /> to <see cref="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.End" /> inclusive.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public int Start { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Start" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.ExitCodeRangeMapping.Start" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Start As Integer" />
      <MemberSignature Language="F#" Value="member this.Start : int" Usage="Microsoft.Azure.Batch.ExitCodeRangeMapping.Start" />
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
            <span data-ttu-id="17be0-110">Ruft den ersten Exitcode im Bereich ab.</span><span class="sxs-lookup"><span data-stu-id="17be0-110">Gets the first exit code in the range.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="17be0-111">Bereiche sind inklusiv.</span><span class="sxs-lookup"><span data-stu-id="17be0-111">Ranges are inclusive.</span></span> <span data-ttu-id="17be0-112">Z. B. wenn ein <see cref="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" /> gibt 8 "und" End 10 starten wird es Exitcodes, 8, 9 und 10 entspricht.</span><span class="sxs-lookup"><span data-stu-id="17be0-112">For example, if an <see cref="T:Microsoft.Azure.Batch.ExitCodeRangeMapping" /> specifies Start 8 and End 10, then it matches exit codes 8, 9 and 10.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>