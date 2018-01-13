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
            Diese Enumeration wird an die Prüfbarkeit Products API, um anzugeben, welche Art von Datenverlust an nachdenken übergeben.
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
            FullDataLoss Option löscht alle Replikate Dies bedeutet, dass alle Daten verloren. 
            </summary>
        <remarks>
            Diese Option ist hilfreich, um die Sicherung und Wiederherstellung Datenpfade zu testen.
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
            Reserviert.  Übergeben Sie diesen Wert nicht an die API.
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
            PartialDataLoss-Option wird ein Quorum der Replikate, fahren Sie nach unten, verursacht das Auslösen eines Ereignisses OnDataLoss in das System für die angegebene Partition. 
            </summary>
        <remarks>
            Gibt an, ob wirklich ein Datenverlust geschieht abhängig, ob Transaktionen mit ausgeführtem Commit, die weiterhin zum Zeitpunkt repliziert wurden der Datenverlust wurde ausgelöst wurden
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>