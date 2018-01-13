<Type Name="ApplicationUpgradeState" FullName="System.Fabric.ApplicationUpgradeState">
  <TypeSignature Language="C#" Value="public enum ApplicationUpgradeState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ApplicationUpgradeState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ApplicationUpgradeState" />
  <TypeSignature Language="VB.NET" Value="Public Enum ApplicationUpgradeState" />
  <TypeSignature Language="F#" Value="type ApplicationUpgradeState = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="3dc44-101">Listet den Status des Anwendungsupgrades.</span><span class="sxs-lookup"><span data-stu-id="3dc44-101">Enumerates the state of the application upgrade.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Failed">
      <MemberSignature Language="C#" Value="Failed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ApplicationUpgradeState Failed = int32(6)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ApplicationUpgradeState.Failed" />
      <MemberSignature Language="VB.NET" Value="Failed" />
      <MemberSignature Language="F#" Value="Failed = 6" Usage="System.Fabric.ApplicationUpgradeState.Failed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ApplicationUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>6</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3dc44-102">Gibt an, dass das Upgrade fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="3dc44-102">Indicates that the upgrade has failed.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ApplicationUpgradeState Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ApplicationUpgradeState.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.ApplicationUpgradeState.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ApplicationUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3dc44-103">Gibt an, dass der Typ nicht gültig ist.</span><span class="sxs-lookup"><span data-stu-id="3dc44-103">Indicates that the type is not valid.</span></span> <span data-ttu-id="3dc44-104">Alle Service Fabric-Enumerationen haben einen ungültigen Typ.</span><span class="sxs-lookup"><span data-stu-id="3dc44-104">All Service Fabric enumerations have an invalid type.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingBackCompleted">
      <MemberSignature Language="C#" Value="RollingBackCompleted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ApplicationUpgradeState RollingBackCompleted = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ApplicationUpgradeState.RollingBackCompleted" />
      <MemberSignature Language="VB.NET" Value="RollingBackCompleted" />
      <MemberSignature Language="F#" Value="RollingBackCompleted = 2" Usage="System.Fabric.ApplicationUpgradeState.RollingBackCompleted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ApplicationUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3dc44-105">Gibt an, dass das Rollback des Upgrades abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="3dc44-105">Indicates that the roll back of the upgrade is completed.</span></span> <span data-ttu-id="3dc44-106">Das abgeschlossene Rollback gibt an, dass das Upgrade auf das Ziel fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="3dc44-106">The completed rollback indicates that upgrade to the target version has failed.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingBackInProgress">
      <MemberSignature Language="C#" Value="RollingBackInProgress" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ApplicationUpgradeState RollingBackInProgress = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ApplicationUpgradeState.RollingBackInProgress" />
      <MemberSignature Language="VB.NET" Value="RollingBackInProgress" />
      <MemberSignature Language="F#" Value="RollingBackInProgress = 1" Usage="System.Fabric.ApplicationUpgradeState.RollingBackInProgress" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ApplicationUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3dc44-107">Gibt an, dass das Upgrade gerade ein Rollback.</span><span class="sxs-lookup"><span data-stu-id="3dc44-107">Indicates that the upgrade is in the process of rolling back.</span></span> <span data-ttu-id="3dc44-108">Dies weist darauf hin, dass das Upgrade auf das Ziel fehlgeschlagen ist.</span><span class="sxs-lookup"><span data-stu-id="3dc44-108">This indicates that upgrade to the target version has failed.</span></span> <span data-ttu-id="3dc44-109">Beachten Sie, die diesem Zustand kann auch sein vorübergehend beobachtet werden, wenn das Upgrade unterbrochen wird, um ein neues Upgrade zu starten.</span><span class="sxs-lookup"><span data-stu-id="3dc44-109">Note that this state can also be observed temporarily if the upgrade is interrupted to start a new upgrade.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingForwardCompleted">
      <MemberSignature Language="C#" Value="RollingForwardCompleted" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ApplicationUpgradeState RollingForwardCompleted = int32(5)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ApplicationUpgradeState.RollingForwardCompleted" />
      <MemberSignature Language="VB.NET" Value="RollingForwardCompleted" />
      <MemberSignature Language="F#" Value="RollingForwardCompleted = 5" Usage="System.Fabric.ApplicationUpgradeState.RollingForwardCompleted" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ApplicationUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>5</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3dc44-110">Gibt an, dass das Upgrade auf die Zielversion des Anwendungstyps abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="3dc44-110">Indicates that the upgrade to the target application type version is completed.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingForwardInProgress">
      <MemberSignature Language="C#" Value="RollingForwardInProgress" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ApplicationUpgradeState RollingForwardInProgress = int32(4)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ApplicationUpgradeState.RollingForwardInProgress" />
      <MemberSignature Language="VB.NET" Value="RollingForwardInProgress" />
      <MemberSignature Language="F#" Value="RollingForwardInProgress = 4" Usage="System.Fabric.ApplicationUpgradeState.RollingForwardInProgress" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ApplicationUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>4</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3dc44-111">Gibt an, dass das Upgrade auf die Zielversion des Anwendungstyps ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="3dc44-111">Indicates that the upgrade to the target application type version is in progress.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="RollingForwardPending">
      <MemberSignature Language="C#" Value="RollingForwardPending" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.ApplicationUpgradeState RollingForwardPending = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.ApplicationUpgradeState.RollingForwardPending" />
      <MemberSignature Language="VB.NET" Value="RollingForwardPending" />
      <MemberSignature Language="F#" Value="RollingForwardPending = 3" Usage="System.Fabric.ApplicationUpgradeState.RollingForwardPending" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ApplicationUpgradeState</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="3dc44-112">Gibt an, dass das Upgrade auf die Zielversion des Anwendungstyps Benutzereingabe aussteht.</span><span class="sxs-lookup"><span data-stu-id="3dc44-112">Indicates that the upgrade to the target application type version is pending user input.</span></span> <span data-ttu-id="3dc44-113">Die <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" /> wird verwendet, um das Upgrade vorwärts zu bewegen.</span><span class="sxs-lookup"><span data-stu-id="3dc44-113">The <see cref="M:System.Fabric.FabricClient.ApplicationManagementClient.MoveNextApplicationUpgradeDomainAsync(System.Fabric.ApplicationUpgradeProgress)" /> is used to move the upgrade forward.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>