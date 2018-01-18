<Type Name="SchedulingState" FullName="Microsoft.Azure.Batch.Protocol.Models.SchedulingState">
  <TypeSignature Language="C#" Value="public enum SchedulingState" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SchedulingState extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.SchedulingState" />
  <TypeSignature Language="VB.NET" Value="Public Enum SchedulingState" />
  <TypeSignature Language="F#" Value="type SchedulingState = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonConverter(typeof(Newtonsoft.Json.Converters.StringEnumConverter))</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="a1b52-101">Definiert Werte für SchedulingState an.</span><span class="sxs-lookup"><span data-stu-id="a1b52-101">Defines values for SchedulingState.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Disabled">
      <MemberSignature Language="C#" Value="Disabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.SchedulingState Disabled = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.SchedulingState.Disabled" />
      <MemberSignature Language="VB.NET" Value="Disabled" />
      <MemberSignature Language="F#" Value="Disabled = 1" Usage="Microsoft.Azure.Batch.Protocol.Models.SchedulingState.Disabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="disabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.SchedulingState</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a1b52-102">Auf dem Knoten werden keine neue Tasks geplant werden.</span><span class="sxs-lookup"><span data-stu-id="a1b52-102">No new tasks will be scheduled on the node.</span></span> <span data-ttu-id="a1b52-103">Aufgaben, die möglicherweise bereits auf dem Knoten ausgeführt noch werden vollständig ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="a1b52-103">Tasks already running on the node may still run to completion.</span></span> <span data-ttu-id="a1b52-104">Alle Knoten beginnen Sie mit Planung aktiviert.</span><span class="sxs-lookup"><span data-stu-id="a1b52-104">All nodes start with scheduling enabled.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="Enabled" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Batch.Protocol.Models.SchedulingState Enabled = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Batch.Protocol.Models.SchedulingState.Enabled" />
      <MemberSignature Language="VB.NET" Value="Enabled" />
      <MemberSignature Language="F#" Value="Enabled = 0" Usage="Microsoft.Azure.Batch.Protocol.Models.SchedulingState.Enabled" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="enabled")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.SchedulingState</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="a1b52-105">Aufgaben können auf dem Knoten geplant werden.</span><span class="sxs-lookup"><span data-stu-id="a1b52-105">Tasks can be scheduled on the node.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>