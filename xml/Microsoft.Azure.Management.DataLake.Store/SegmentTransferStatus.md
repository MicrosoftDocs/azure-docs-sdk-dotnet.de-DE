<Type Name="SegmentTransferStatus" FullName="Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus">
  <TypeSignature Language="C#" Value="public enum SegmentTransferStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed SegmentTransferStatus extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus" />
  <TypeSignature Language="VB.NET" Value="Public Enum SegmentTransferStatus" />
  <TypeSignature Language="F#" Value="type SegmentTransferStatus = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
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
            <span data-ttu-id="297bf-101">Definiert verschiedene Zustände, die eine Übertragung Segment aufweisen können</span><span class="sxs-lookup"><span data-stu-id="297bf-101">Defines various states that a segment transfer can have</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Complete">
      <MemberSignature Language="C#" Value="Complete" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus Complete = int32(3)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus.Complete" />
      <MemberSignature Language="VB.NET" Value="Complete" />
      <MemberSignature Language="F#" Value="Complete = 3" Usage="Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus.Complete" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="Complete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus</ReturnType>
      </ReturnValue>
      <MemberValue>3</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="297bf-102">Gibt an, dass das Segment erfolgreich übertragen wurde.</span><span class="sxs-lookup"><span data-stu-id="297bf-102">Indicates that the segment was successfully transferred.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Failed">
      <MemberSignature Language="C#" Value="Failed" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus Failed = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus.Failed" />
      <MemberSignature Language="VB.NET" Value="Failed" />
      <MemberSignature Language="F#" Value="Failed = 2" Usage="Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus.Failed" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="Failed")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="297bf-103">Gibt an, dass das Segment nicht erfolgreich übertragen wurde.</span><span class="sxs-lookup"><span data-stu-id="297bf-103">Indicates that the segment was not transferred successfully.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="InProgress">
      <MemberSignature Language="C#" Value="InProgress" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus InProgress = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus.InProgress" />
      <MemberSignature Language="VB.NET" Value="InProgress" />
      <MemberSignature Language="F#" Value="InProgress = 1" Usage="Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus.InProgress" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="InProgress")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="297bf-104">Gibt an, dass das Segment gegenwärtig übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="297bf-104">Indicates that the segment is currently being transferred.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="Pending">
      <MemberSignature Language="C#" Value="Pending" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus Pending = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus.Pending" />
      <MemberSignature Language="VB.NET" Value="Pending" />
      <MemberSignature Language="F#" Value="Pending = 0" Usage="Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus.Pending" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.Serialization.EnumMember(Value="Pending")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.DataLake.Store.SegmentTransferStatus</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="297bf-105">Gibt an, dass das Segment gegenwärtig für die Übertragung geplant ist.</span><span class="sxs-lookup"><span data-stu-id="297bf-105">Indicates that the segment is currently scheduled for transfer.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>