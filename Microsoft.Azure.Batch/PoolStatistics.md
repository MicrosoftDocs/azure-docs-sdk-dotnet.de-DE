<Type Name="PoolStatistics" FullName="Microsoft.Azure.Batch.PoolStatistics">
  <TypeSignature Language="C#" Value="public class PoolStatistics" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolStatistics extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PoolStatistics" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolStatistics" />
  <TypeSignature Language="F#" Value="type PoolStatistics = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="3db84-101">Enthält Auslastung und Ressource Nutzungsstatistiken für die Lebensdauer eines Pools.</span><span class="sxs-lookup"><span data-stu-id="3db84-101">Contains utilization and resource usage statistics for the lifetime of a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="LastUpdateTime">
      <MemberSignature Language="C#" Value="public DateTime LastUpdateTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastUpdateTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolStatistics.LastUpdateTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastUpdateTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastUpdateTime : DateTime" Usage="Microsoft.Azure.Batch.PoolStatistics.LastUpdateTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3db84-102">Ruft den Zeitpunkt, an dem die Statistik zuletzt aktualisiert wurden.</span><span class="sxs-lookup"><span data-stu-id="3db84-102">Gets the time at which the statistics were last updated.</span></span> <span data-ttu-id="3db84-103">Alle Statistiken sind beschränkt auf den Bereich zwischen <see cref="P:Microsoft.Azure.Batch.PoolStatistics.StartTime" /> und diesen Wert.</span><span class="sxs-lookup"><span data-stu-id="3db84-103">All statistics are limited to the range between <see cref="P:Microsoft.Azure.Batch.PoolStatistics.StartTime" /> and this value.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceStatistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ResourceStatistics ResourceStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ResourceStatistics ResourceStatistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolStatistics.ResourceStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceStatistics As ResourceStatistics" />
      <MemberSignature Language="F#" Value="member this.ResourceStatistics : Microsoft.Azure.Batch.ResourceStatistics" Usage="Microsoft.Azure.Batch.PoolStatistics.ResourceStatistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ResourceStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3db84-104">Ruft Statistiken in Bezug auf den Ressourcenverbrauch durch Serverknoten im Pool, z. B. die durchschnittliche CPU-Auslastung an.</span><span class="sxs-lookup"><span data-stu-id="3db84-104">Gets statistics related to resource consumption by compute nodes in the pool, such as average CPU utilization.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTime">
      <MemberSignature Language="C#" Value="public DateTime StartTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime StartTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolStatistics.StartTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.StartTime : DateTime" Usage="Microsoft.Azure.Batch.PoolStatistics.StartTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3db84-105">Ruft die Startzeit des Zeitraums, der von den Statistiken abgedeckt.</span><span class="sxs-lookup"><span data-stu-id="3db84-105">Gets the start time of the time range covered by the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolStatistics.Url" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string" Usage="Microsoft.Azure.Batch.PoolStatistics.Url" />
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
            <span data-ttu-id="3db84-106">Ruft die URL für die Statistik ab.</span><span class="sxs-lookup"><span data-stu-id="3db84-106">Gets the URL for the statistics.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageStatistics">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.UsageStatistics UsageStatistics { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.UsageStatistics UsageStatistics" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolStatistics.UsageStatistics" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageStatistics As UsageStatistics" />
      <MemberSignature Language="F#" Value="member this.UsageStatistics : Microsoft.Azure.Batch.UsageStatistics" Usage="Microsoft.Azure.Batch.PoolStatistics.UsageStatistics" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.UsageStatistics</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3db84-107">Ruft Statistiken zur Nutzung des Arbeitsthreadpools, z. B. die verstrichene Zeitspanne Core-verwendet.</span><span class="sxs-lookup"><span data-stu-id="3db84-107">Gets statistics related to pool usage, such as the amount of core-time used.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>