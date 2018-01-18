<Type Name="ActorCallType" FullName="Microsoft.ServiceFabric.Actors.Runtime.ActorCallType">
  <TypeSignature Language="C#" Value="public enum ActorCallType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed ActorCallType extends System.Enum" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Actors.Runtime.ActorCallType" />
  <TypeSignature Language="VB.NET" Value="Public Enum ActorCallType" />
  <TypeSignature Language="F#" Value="type ActorCallType = " />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Enum</BaseTypeName>
  </Base>
  <Docs>
    <summary>
            <span data-ttu-id="6fcac-101">Stellt den Aufruf-Typ der Methode aufgerufen, indem Akteur-Laufzeit zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="6fcac-101">Represents the call-type associated with the method invoked by actor runtime.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="6fcac-102">Dies erfolgt im Rahmen des <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" /> der als Argument übergeben wird <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPreActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" /> und <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPostActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" />.</span><span class="sxs-lookup"><span data-stu-id="6fcac-102">This is provided as part of <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext" /> which is passed as argument to <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPreActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" /> and <see cref="M:Microsoft.ServiceFabric.Actors.Runtime.ActorBase.OnPostActorMethodAsync(Microsoft.ServiceFabric.Actors.Runtime.ActorMethodContext)" />.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="ActorInterfaceMethod">
      <MemberSignature Language="C#" Value="ActorInterfaceMethod" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorCallType ActorInterfaceMethod = int32(0)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.ActorCallType.ActorInterfaceMethod" />
      <MemberSignature Language="VB.NET" Value="ActorInterfaceMethod" />
      <MemberSignature Language="F#" Value="ActorInterfaceMethod = 0" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorCallType.ActorInterfaceMethod" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorCallType</ReturnType>
      </ReturnValue>
      <MemberValue>0</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fcac-103">Gibt an, dass die aufgerufene Methode eine Schnittstellenmethode Akteur für eine bestimmte Clientanforderung.</span><span class="sxs-lookup"><span data-stu-id="6fcac-103">Specifies that the method invoked is an actor interface method for a given client request.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="ReminderMethod">
      <MemberSignature Language="C#" Value="ReminderMethod" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorCallType ReminderMethod = int32(2)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.ActorCallType.ReminderMethod" />
      <MemberSignature Language="VB.NET" Value="ReminderMethod" />
      <MemberSignature Language="F#" Value="ReminderMethod = 2" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorCallType.ReminderMethod" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorCallType</ReturnType>
      </ReturnValue>
      <MemberValue>2</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fcac-104">Gibt an, dass die Methode aufgerufen wird, auf <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> Schnittstelle, wenn eine Erinnerung ausgelöst wird.</span><span class="sxs-lookup"><span data-stu-id="6fcac-104">Specifies that the method invoked on <see cref="T:Microsoft.ServiceFabric.Actors.Runtime.IRemindable" /> interface when a reminder fires.</span></span>
            </summary>
      </Docs>
    </Member>
    <Member MemberName="TimerMethod">
      <MemberSignature Language="C#" Value="TimerMethod" />
      <MemberSignature Language="ILAsm" Value=".field public static literal valuetype Microsoft.ServiceFabric.Actors.Runtime.ActorCallType TimerMethod = int32(1)" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceFabric.Actors.Runtime.ActorCallType.TimerMethod" />
      <MemberSignature Language="VB.NET" Value="TimerMethod" />
      <MemberSignature Language="F#" Value="TimerMethod = 1" Usage="Microsoft.ServiceFabric.Actors.Runtime.ActorCallType.TimerMethod" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Actors</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Actors.Runtime.ActorCallType</ReturnType>
      </ReturnValue>
      <MemberValue>1</MemberValue>
      <Docs>
        <summary>
            <span data-ttu-id="6fcac-105">Gibt an, dass die aufgerufene Methode eine Rückrufmethode Timer.</span><span class="sxs-lookup"><span data-stu-id="6fcac-105">Specifies that the method invoked is a timer callback method.</span></span>
            </summary>
      </Docs>
    </Member>
  </Members>
</Type>