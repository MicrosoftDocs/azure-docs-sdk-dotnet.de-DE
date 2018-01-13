<Type Name="UpgradeFailureAction" FullName="System.Fabric.UpgradeFailureAction">
  <TypeSignature Language="C#" Value="public enum UpgradeFailureAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed UpgradeFailureAction extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.UpgradeFailureAction" />
  <TypeSignature Language="VB.NET" Value="Public Enum UpgradeFailureAction" />
  <TypeSignature Language="F#" Value="type UpgradeFailureAction = " />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
      <para>Listet die Aktionen für Service Fabric an, wenn das Upgrade fehlschlägt.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Invalid">
      <MemberSignature Language="C#" Value="Invalid" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeFailureAction Invalid = int32(0)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeFailureAction.Invalid" />
      <MemberSignature Language="VB.NET" Value="Invalid" />
      <MemberSignature Language="F#" Value="Invalid = 0" Usage="System.Fabric.UpgradeFailureAction.Invalid" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureAction</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass dieses Upgrade ungültig ist. Alle Service Fabric-Enumerationen wurde ein ungültiger Typ.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Manual">
      <MemberSignature Language="C#" Value="Manual" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeFailureAction Manual = int32(2)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeFailureAction.Manual" />
      <MemberSignature Language="VB.NET" Value="Manual" />
      <MemberSignature Language="F#" Value="Manual = 2" Usage="System.Fabric.UpgradeFailureAction.Manual" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureAction</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass eine manuelle Reparatur muss vom Administrator ausgeführt werden, wenn das Upgrade fehlschlägt. Service Fabric wird nicht automatisch mit der nächsten upgradedomäne fortgesetzt.</para>
        </summary>
      </Docs>
    </Member>
    <Member MemberName="Rollback">
      <MemberSignature Language="C#" Value="Rollback" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype System.Fabric.UpgradeFailureAction Rollback = int32(1)" />
      <MemberSignature Language="DocId" Value="F:System.Fabric.UpgradeFailureAction.Rollback" />
      <MemberSignature Language="VB.NET" Value="Rollback" />
      <MemberSignature Language="F#" Value="Rollback = 1" Usage="System.Fabric.UpgradeFailureAction.Rollback" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.UpgradeFailureAction</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
          <para>Gibt an, dass ein Rollback des Upgrades von Service Fabric ausgeführt wird, wenn das Upgrade fehlschlägt.</para>
        </summary>
      </Docs>
    </Member>
  </Members>
</Type>