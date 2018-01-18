<Type Name="NodeUpgradePhase" FullName="System.Fabric.NodeUpgradePhase">
  <TypeSignature Language="C#" Value="public enum NodeUpgradePhase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed NodeUpgradePhase extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.NodeUpgradePhase" />
  <TypeSignature Language="VB.NET" Value="Public Enum NodeUpgradePhase" />
  <TypeSignature Language="F#" Value="type NodeUpgradePhase = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para><span data-ttu-id="db553-101">Beschreibt die Phase des Upgrade des entsprechenden Knotens an.</span><span class="sxs-lookup"><span data-stu-id="db553-101">Describes the upgrade phase of the corresponding node.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeUpgradePhase Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeUpgradePhase.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.NodeUpgradePhase.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeUpgradePhase</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="db553-102">Gibt an, dass die knotenupgradephase ungültig ist.</span><span class="sxs-lookup"><span data-stu-id="db553-102">Indicates that the node upgrade phase is invalid.</span></span> <span data-ttu-id="db553-103">Dieser Wert wird nicht verwendet.</span><span class="sxs-lookup"><span data-stu-id="db553-103">This value is not used.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="PostUpgradeSafetyCheck">
      <MemberSignature Language="C#" Value="PostUpgradeSafetyCheck" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeUpgradePhase PostUpgradeSafetyCheck = int32(3)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeUpgradePhase.PostUpgradeSafetyCheck" />
      <MemberSignature Language="VB.NET" Value="PostUpgradeSafetyCheck" />
      <MemberSignature Language="F#" Value="PostUpgradeSafetyCheck = 3" Usage="System.Fabric.NodeUpgradePhase.PostUpgradeSafetyCheck" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeUpgradePhase</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="db553-104">Gibt an, dass-Upgrade abgeschlossen auf dem Knoten ist und Fabric-Dienst nach dem upgrade sicherheitsüberprüfungen ausführt.</span><span class="sxs-lookup"><span data-stu-id="db553-104">Indicates that upgrade is complete on the node and Service Fabric is performing post-upgrade safety checks.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="PreUpgradeSafetyCheck">
      <MemberSignature Language="C#" Value="PreUpgradeSafetyCheck" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeUpgradePhase PreUpgradeSafetyCheck = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeUpgradePhase.PreUpgradeSafetyCheck" />
      <MemberSignature Language="VB.NET" Value="PreUpgradeSafetyCheck" />
      <MemberSignature Language="F#" Value="PreUpgradeSafetyCheck = 1" Usage="System.Fabric.NodeUpgradePhase.PreUpgradeSafetyCheck" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeUpgradePhase</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="db553-105">Gibt an, dass Upgrade auf den Knoten nicht gestartet wurde und Service Fabric vor dem upgrade sicherheitsüberprüfungen ausführt.</span><span class="sxs-lookup"><span data-stu-id="db553-105">Indicates that upgrade has not started on the node and Service Fabric is performing pre-upgrade safety checks.</span></span></para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Upgrading">
      <MemberSignature Language="C#" Value="Upgrading" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.NodeUpgradePhase Upgrading = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.NodeUpgradePhase.Upgrading" />
      <MemberSignature Language="VB.NET" Value="Upgrading" />
      <MemberSignature Language="F#" Value="Upgrading = 2" Usage="System.Fabric.NodeUpgradePhase.Upgrading" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeUpgradePhase</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="db553-106">Gibt an, dass der Knoten gerade aktualisiert wird.</span><span class="sxs-lookup"><span data-stu-id="db553-106">Indicates that the node is in the process of getting upgraded.</span></span></para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>