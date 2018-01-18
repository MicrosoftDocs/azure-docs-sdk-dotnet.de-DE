<Type Name="Utilities" FullName="Microsoft.Azure.Batch.Utilities">
  <TypeSignature Language="C#" Value="public class Utilities : Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Utilities extends System.Object implements class Microsoft.Azure.Batch.IInheritedBehaviors" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Utilities" />
  <TypeSignature Language="VB.NET" Value="Public Class Utilities&#xA;Implements IInheritedBehaviors" />
  <TypeSignature Language="F#" Value="type Utilities = class&#xA;    interface IInheritedBehaviors" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.IInheritedBehaviors</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="99064-101">Tools und Hilfsprogramme für den Azure Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="99064-101">Tools and utilities for the Azure Batch Service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateTaskStateMonitor">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.TaskStateMonitor CreateTaskStateMonitor ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Batch.TaskStateMonitor CreateTaskStateMonitor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Utilities.CreateTaskStateMonitor" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateTaskStateMonitor () As TaskStateMonitor" />
      <MemberSignature Language="F#" Value="member this.CreateTaskStateMonitor : unit -&gt; Microsoft.Azure.Batch.TaskStateMonitor" Usage="utilities.CreateTaskStateMonitor " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.TaskStateMonitor</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="99064-102">Erstellt eine TaskStateMonitor an.</span><span class="sxs-lookup"><span data-stu-id="99064-102">Creates an TaskStateMonitor.</span></span>
            </summary>
        <returns><span data-ttu-id="99064-103">Eine <see cref="T:Microsoft.Azure.Batch.TaskStateMonitor" />-Instanz.</span><span class="sxs-lookup"><span data-stu-id="99064-103">A <see cref="T:Microsoft.Azure.Batch.TaskStateMonitor" /> instance.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Utilities.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.Utilities.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.IInheritedBehaviors.CustomBehaviors</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="99064-104">Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst, die über dieses <see cref="T:Microsoft.Azure.Batch.Utilities" />.</span><span class="sxs-lookup"><span data-stu-id="99064-104">Gets or sets a list of behaviors that modify or customize requests to the Batch service made via this <see cref="T:Microsoft.Azure.Batch.Utilities" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para><span data-ttu-id="99064-105">Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</span><span class="sxs-lookup"><span data-stu-id="99064-105">These behaviors are inherited by child objects.</span></span></para>
          <para><span data-ttu-id="99064-106">Änderungen werden in der Reihenfolge der Auflistung angewendet.</span><span class="sxs-lookup"><span data-stu-id="99064-106">Modifications are applied in the order of the collection.</span></span> <span data-ttu-id="99064-107">Der letzte write Wins.</span><span class="sxs-lookup"><span data-stu-id="99064-107">The last write wins.</span></span></para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>