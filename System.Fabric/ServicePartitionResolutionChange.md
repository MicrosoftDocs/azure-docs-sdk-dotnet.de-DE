<Type Name="ServicePartitionResolutionChange" FullName="System.Fabric.ServicePartitionResolutionChange">
  <TypeSignature Language="C#" Value="public sealed class ServicePartitionResolutionChange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServicePartitionResolutionChange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServicePartitionResolutionChange" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServicePartitionResolutionChange" />
  <TypeSignature Language="F#" Value="type ServicePartitionResolutionChange = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>Dieser Wrapper enthält die aktualisierte <see cref="T:System.Fabric.ResolvedServicePartition" />. </para>
    </summary>
    <remarks>
      <para>Wenn es eine Ausnahme ausgelöst werden, während die neueren wurde <see cref="T:System.Fabric.ResolvedServicePartition" /> eingerichtet, und klicken Sie dann die <see cref="T:System.Fabric.ServicePartitionResolutionChange" /> enthält auch die Ausnahme. Beachten Sie, dass bei der <see cref="P:System.Fabric.ServicePartitionResolutionChange.Exception" /> -Eigenschaft nicht null ist, und klicken Sie dann die <see cref="P:System.Fabric.ServicePartitionResolutionChange.Result" /> -Eigenschaft null ist.</para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServicePartitionResolutionChange.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="System.Fabric.ServicePartitionResolutionChange.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Ruft die Ausnahme, die ausgelöst wurde, während die relevanten <see cref="T:System.Fabric.ResolvedServicePartition" /> , die abgerufen oder aktualisiert wurde.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Exception" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasException">
      <MemberSignature Language="C#" Value="public bool HasException { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasException" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServicePartitionResolutionChange.HasException" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasException As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasException : bool" Usage="System.Fabric.ServicePartitionResolutionChange.HasException" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Gibt an, ob eine Ausnahme aufgetreten. </para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Boolean" />zurück.</para>
        </value>
        <remarks>
          <para>Wenn dies der Fall ist, die <see cref="P:System.Fabric.ServicePartitionResolutionChange.Result" /> Parameter null ist und die <see cref="P:System.Fabric.ServicePartitionResolutionChange.Exception" /> Parameter festgelegt ist.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServicePartition Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ResolvedServicePartition Result" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServicePartitionResolutionChange.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As ResolvedServicePartition" />
      <MemberSignature Language="F#" Value="member this.Result : System.Fabric.ResolvedServicePartition" Usage="System.Fabric.ServicePartitionResolutionChange.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Enthält die neuen <see cref="T:System.Fabric.ResolvedServicePartition" /> , für die registrierten Dienstpartition relevant ist.</para>
        </summary>
        <value>
          <para>Gibt <see cref="T:System.Fabric.ResolvedServicePartition" />zurück.</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>