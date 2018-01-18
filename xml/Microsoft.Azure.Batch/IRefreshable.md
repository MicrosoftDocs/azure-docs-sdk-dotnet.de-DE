<Type Name="IRefreshable" FullName="Microsoft.Azure.Batch.IRefreshable">
  <TypeSignature Language="C#" Value="public interface IRefreshable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IRefreshable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.IRefreshable" />
  <TypeSignature Language="VB.NET" Value="Public Interface IRefreshable" />
  <TypeSignature Language="F#" Value="type IRefreshable = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7cded-101">Bietet einen Mechanismus zum Aktualisieren einer Ressourcenpools.</span><span class="sxs-lookup"><span data-stu-id="7cded-101">Provides a mechanism for refreshing a resource.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Refresh">
      <MemberSignature Language="C#" Value="public void Refresh (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Refresh(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.IRefreshable.Refresh(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior})" />
      <MemberSignature Language="F#" Value="abstract member Refresh : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; -&gt; unit" Usage="iRefreshable.Refresh (detailLevel, additionalBehaviors)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="7cded-102">Steuert die Detailebene der Daten durch einen Aufruf der Azure Batch-Dienst zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="7cded-102">Controls the detail level of the data returned by a call to the Azure Batch Service.</span></span> <span data-ttu-id="7cded-103">Wenn eine Detailebene, die weglässt die Eigenschaft "Name" angegeben wird, schlägt die Aktualisierung fehl.</span><span class="sxs-lookup"><span data-stu-id="7cded-103">If a detail level which omits the "Name" property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="7cded-104">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="7cded-104">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <summary>
            <span data-ttu-id="7cded-105">Blockierenden Aufruf Erzwingen der Aktualisierung des aktuellen Objekts.</span><span class="sxs-lookup"><span data-stu-id="7cded-105">Blocking call to force a refresh of the current object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RefreshAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RefreshAsync (Microsoft.Azure.Batch.DetailLevel detailLevel = null, System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RefreshAsync(class Microsoft.Azure.Batch.DetailLevel detailLevel, class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; additionalBehaviors, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.IRefreshable.RefreshAsync(Microsoft.Azure.Batch.DetailLevel,System.Collections.Generic.IEnumerable{Microsoft.Azure.Batch.BatchClientBehavior},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RefreshAsync : Microsoft.Azure.Batch.DetailLevel * seq&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iRefreshable.RefreshAsync (detailLevel, additionalBehaviors, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="detailLevel" Type="Microsoft.Azure.Batch.DetailLevel" />
        <Parameter Name="additionalBehaviors" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="detailLevel"><span data-ttu-id="7cded-106">Steuert die Detailebene der Daten durch einen Aufruf der Azure Batch-Dienst zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="7cded-106">Controls the detail level of the data returned by a call to the Azure Batch Service.</span></span>  <span data-ttu-id="7cded-107">Wenn eine Detailebene, die weglässt die Eigenschaft "Name" angegeben wird, schlägt die Aktualisierung fehl.</span><span class="sxs-lookup"><span data-stu-id="7cded-107">If a detail level which omits the "Name" property is specified, refresh will fail.</span></span></param>
        <param name="additionalBehaviors"><span data-ttu-id="7cded-108">Eine Auflistung von BatchClientBehavior-Instanzen, die nach der CustomBehaviors für das aktuelle Objekt angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="7cded-108">A collection of BatchClientBehavior instances that are applied after the CustomBehaviors on the current object.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="7cded-109">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="7cded-109">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="7cded-110">Startet die asynchronen Aufruf, um das aktuelle Objekt zu aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="7cded-110">Begins asynchronous call to refresh the current object.</span></span>
            </summary>
        <returns><span data-ttu-id="7cded-111">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="7cded-111">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>