<Type Name="DataLossMode" FullName="System.Fabric.DataLossMode">
  <TypeSignature Language="C#" Value="public enum DataLossMode" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed DataLossMode extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.DataLossMode" />
  <TypeSignature Language="VB.NET" Value="Public Enum DataLossMode" />
  <TypeSignature Language="F#" Value="type DataLossMode = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="449a2-101">Diese Enumeration wird an die Prüfbarkeit Products API, um anzugeben, welche Art von Datenverlust an nachdenken übergeben.</span><span class="sxs-lookup"><span data-stu-id="449a2-101">This enum is passed to the DataLoss testability API to indicate what type of data loss to induce.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="FullDataLoss">
      <MemberSignature Language="C#" Value="FullDataLoss" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.DataLossMode FullDataLoss = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.DataLossMode.FullDataLoss" />
      <MemberSignature Language="VB.NET" Value="FullDataLoss" />
      <MemberSignature Language="F#" Value="FullDataLoss = 2" Usage="System.Fabric.DataLossMode.FullDataLoss" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.DataLossMode</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="449a2-102">FullDataLoss Option löscht alle Replikate Dies bedeutet, dass alle Daten verloren.</span><span class="sxs-lookup"><span data-stu-id="449a2-102">FullDataLoss option will drop all the replicas which means that all the data will be lost.</span></span> 
            </summary>
        <remarks>
            <span data-ttu-id="449a2-103">Diese Option ist hilfreich, um die Sicherung und Wiederherstellung Datenpfade zu testen.</span><span class="sxs-lookup"><span data-stu-id="449a2-103">This option is very useful to test out backup and recovery data paths.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.DataLossMode Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.DataLossMode.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.DataLossMode.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.DataLossMode</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="449a2-104">Reserviert.</span><span class="sxs-lookup"><span data-stu-id="449a2-104">Reserved.</span></span>  <span data-ttu-id="449a2-105">Übergeben Sie diesen Wert nicht an die API.</span><span class="sxs-lookup"><span data-stu-id="449a2-105">Do not pass into API.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="PartialDataLoss">
      <MemberSignature Language="C#" Value="PartialDataLoss" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.DataLossMode PartialDataLoss = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.DataLossMode.PartialDataLoss" />
      <MemberSignature Language="VB.NET" Value="PartialDataLoss" />
      <MemberSignature Language="F#" Value="PartialDataLoss = 1" Usage="System.Fabric.DataLossMode.PartialDataLoss" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.DataLossMode</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="449a2-106">PartialDataLoss-Option wird ein Quorum der Replikate, fahren Sie nach unten, verursacht das Auslösen eines Ereignisses OnDataLoss in das System für die angegebene Partition.</span><span class="sxs-lookup"><span data-stu-id="449a2-106">PartialDataLoss option will cause a quorum of replicas to go down, triggering an OnDataLoss event in the system for the given partition.</span></span> 
            </summary>
        <remarks>
            <span data-ttu-id="449a2-107">Gibt an, ob wirklich ein Datenverlust geschieht abhängig, ob Transaktionen mit ausgeführtem Commit, die weiterhin zum Zeitpunkt repliziert wurden der Datenverlust wurde ausgelöst wurden</span><span class="sxs-lookup"><span data-stu-id="449a2-107">Whether actual data loss happens depends on whether there were committed transactions that were still being replicated at the time the data loss was induced</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>