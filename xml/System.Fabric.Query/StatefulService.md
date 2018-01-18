<Type Name="StatefulService" FullName="System.Fabric.Query.StatefulService">
  <TypeSignature Language="C#" Value="public sealed class StatefulService : System.Fabric.Query.Service" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit StatefulService extends System.Fabric.Query.Service" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.StatefulService" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class StatefulService&#xA;Inherits Service" />
  <TypeSignature Language="F#" Value="type StatefulService = class&#xA;    inherit Service" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Query.Service</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="5a921-101">Stellt einen zustandsbehafteten Dienst dar.</span><span class="sxs-lookup"><span data-stu-id="5a921-101">Represents a stateful service.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="HasPersistedState">
      <MemberSignature Language="C#" Value="public bool HasPersistedState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasPersistedState" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.StatefulService.HasPersistedState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasPersistedState As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasPersistedState : bool" Usage="System.Fabric.Query.StatefulService.HasPersistedState" />
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
          <para><span data-ttu-id="5a921-102">Ruft einen Wert, der bestimmt, ob der aktuelle Dienst einen persistenten Zustand aufweist.</span><span class="sxs-lookup"><span data-stu-id="5a921-102">Gets a value that determines whether the current service has persisted state.</span></span></para>
        </summary>
        <value>
          <para>
            <span data-ttu-id="5a921-103"><languageKeyword>"true"</languageKeyword> , wenn der aktuelle Dienst, Zustand befindet, andernfalls beibehalten wurde <languageKeyword>"false"</languageKeyword>.</span><span class="sxs-lookup"><span data-stu-id="5a921-103"><languageKeyword>true</languageKeyword> if the current service has persisted state; otherwise, <languageKeyword>false</languageKeyword>.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>